# PRODIGY_Cybersecurity_04
# A basic keylogger program that logs keystrokes and saves them to a file.

## 🛠️ Project Overview
This is a **basic keylogger program** that records and logs keystrokes in a text file. It uses the `pynput` library to listen for keystrokes and saves them in `keylog.txt`. This project is for **educational and ethical cybersecurity research purposes only**.

## ⚠️ Disclaimer
**This tool is meant for ethical use only.** Unauthorized use of keyloggers is illegal and may lead to legal consequences. Use this only on systems where you have explicit permission.

---

## 📌 Features
✅ Logs all keystrokes, including special keys (Shift, Enter, etc.)  
✅ Saves keystrokes to `keylog.txt`  
✅ Runs in the background  
✅ Lightweight and easy to use  

---

## 🚀 Installation & Setup

### 🔹 Step 1: Clone the Repository
```bash
git clone https://github.com/<your-username>/simple-keylogger.git
cd simple-keylogger
```

### 🔹 Step 2: Install Dependencies
Make sure Python is installed, then run:
```bash
pip install pynput
```

### 🔹 Step 3: Run the Keylogger
```bash
python keylogger.py
```

### 🔹 Step 4: View Logged Keystrokes
```bash
cat keylog.txt  # Linux/Mac
```
```powershell
type keylog.txt  # Windows
```

---

## ⚙️ How It Works
- Uses `pynput` to listen to keyboard inputs.
- Saves each keystroke in `keylog.txt`.
- Runs continuously until manually stopped.
- Can detect both normal and special keys.

---

## ❌ Stop the Keylogger
Press **Ctrl + C** in the terminal to stop the script.

---

## 🌟 Future Enhancements (Ideas to Improve)
🔹 Encrypt logs before saving  
🔹 Send logs via email  
🔹 Add stealth mode (hide terminal output)  

---

## 🏆 Contributing
Pull requests are welcome! Feel free to **fork this repository**, create a new branch, and submit a PR.

---

## 📜 License
This project is licensed under the **MIT License**.

---

## DEMO 📸 
![4project](https://github.com/user-attachments/assets/1d7d6fa5-bee1-4b26-bf91-fabd3bb70eec)


## 📢 Important Notice
**DO NOT use this tool for malicious purposes.** Ethical hacking and penetration testing should always be conducted with proper authorization.

