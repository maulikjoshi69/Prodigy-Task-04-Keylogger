# 🔐 Prodigy-Task-04-Keylogger

This is **Task 4** of the Prodigy Internship Program. The task involves building a simple **Keylogger** using Python that captures keyboard input and logs each key press along with a timestamp.

## 📌 Features

- Captures all keystrokes in real-time
- Logs key presses with precise timestamps
- Stores output in a plain text file (`keylog.txt`)
- Simple and lightweight Python implementation

## ⚠️ Disclaimer

> This project is intended strictly for **educational purposes**. Unauthorized use of keyloggers may be illegal and unethical. Always obtain proper consent before running this tool on any system.

## 💡 How It Works

- Uses the `pynput` library to listen to keyboard events
- Logs the keys pressed and timestamps them
- Saves logs into `keylog.txt` continuously until stopped

## 🧪 Requirements

- Python 3.x
- `pynput` library

Install dependencies using pip:

```bash
pip install pynput
