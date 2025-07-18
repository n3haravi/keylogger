# Python Keylogger

This project is a basic **keylogger** built using Python. It captures keyboard inputs and logs them to a file for monitoring and educational purposes. This was built to understand how input hooks work at a low level in Python.

 **Disclaimer**: This project is for **educational purposes only**. Do **not** use it for unethical or malicious purposes.

---

# Concepts Implemented

- Keyboard event listening using `pynput`
- Logging keystrokes to a text file
- Running the script silently in the background
- Basic file handling in Python

---

 # Tools Used

- **Python 3**
- [`pynput`](https://pypi.org/project/pynput/) library for capturing keypresses
- Terminal (CLI)

---

##  Workflow

1. **Keyboard Listener Setup**  
   The script listens for every key pressed on the keyboard using a `pynput` listener.

2. **Log to File**  
   Each key is recorded into a log file named `log.txt`.

3. **Special Key Handling**  
   Keys like `Enter`, `Space`, `Backspace`, etc., are written in a readable format.

---

## 📸 Screenshot

<img width="1828" height="973" alt="Screenshot (1563)" src="https://github.com/user-attachments/assets/573c326b-b48a-4590-b1ac-9b5f38cb498b" />


## 📚 What I Learned!

1. How to use the `pynput` library for capturing real-time keyboard input  
2. Handling special keys and character formatting  
3. Logging data securely and clearly  
4. Understanding ethical boundaries of keylogging tools

---

##  Next Steps / Ideas

- Add email sending functionality for logs  
- Run as a background process on startup  
- Encrypt the log file for security

---

## Credits

Inspired by simple keylogging examples and security research content. Built with an intent to learn more about **system hooks**, **keyboard events**, and **ethical hacking basics**.



