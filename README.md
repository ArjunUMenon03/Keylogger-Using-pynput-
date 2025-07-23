# Keylogger Using `pynput`

This Python script implements a basic keylogger that captures keystrokes in real-time and logs them into a text file. It records every key pressed by the user and saves the data in batches to a log file named `key_log.txt`.

---

## Features

- Captures keyboard input using the `pynput` library.
- Stores keystrokes in batches (every 10 keys) to improve efficiency.
- Handles special keys like space (writes a newline) and ignores other control key formatting in the log file.
- Stops logging gracefully on pressing the Escape (`Esc`) key.
- Logs are appended continuously to the file to preserve history.

---

## Requirements

- Python 3.x  
- [`pynput` library](https://pypi.org/project/pynput/)

Install `pynput` via pip:

pip install pynput


---

## How It Works

1. The script listens for keyboard events.
2. Keystrokes are stored in a list.
3. Once 10 keys are pressed, they are written to the log file (`key_log.txt`).
4. Special formatting removes quotes and interprets spaces as new lines.
5. The listener stops recording when the Escape key (`Esc`) is pressed.

---

## Usage

1. Save the script as `keylogger.py`.
2. Run the script in a terminal or command prompt:

hello worl
d
this is a
test


---

## Author

Arjun U Menon

---

## License

This tool is intended strictly for educational purposes. The author is not responsible for misuse.
