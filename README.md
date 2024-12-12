# Keylogger Script

This project provides a simple keylogger implemented in Python using the `pynput` library. The keylogger captures keyboard inputs and logs them into a text file (`keyfile.txt`) for analysis or debugging purposes.

---

## Features

- **Keyboard Input Logging**: Records all keystrokes, including special keys, and saves them to a text file.
- **Real-Time Monitoring**: Captures keystrokes as they are typed.
- **Lightweight Design**: Built with minimal dependencies using the `pynput` library.

---

## Prerequisites

- Python 3.6 or later
- `pynput` library

### Installing Dependencies

To install the required library, run:
```bash
pip install pynput
```

---

## Usage

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Run the Script**:
   ```bash
   python keylogger.py
   ```

3. **Monitor Output**:
   - All keystrokes will be logged to `keyfile.txt` in the same directory as the script.

---

## File Structure

```
.
├── keylogger.py    # Keylogger script
└── keyfile.txt     # Output file for logged keystrokes
```

---

## Notes

- This script is for educational purposes and debugging only. Unauthorized use of keyloggers is illegal and unethical.
- The script logs keys in real-time but may not fully capture all special key combinations.
- Ensure appropriate permissions for accessing and modifying the output file (`keyfile.txt`).

---

## License

This project is released under the MIT License. Ensure compliance with local laws and ethical guidelines when using this script.

