# 🧩 REX: Reverse Engineering Automation Tool

REX (Reverse Engineering eXpert) is a lightweight automated static analysis tool designed to assist malware analysts and reverse engineers. It provides file fingerprinting, entropy analysis, string extraction, section parsing (ELF/PE), and YARA rule matching in one click, so analysts can save time and focus on deeper analysis.

## 🚀 Features

✅ Automated static analysis (SHA-256 hash, entropy, file type detection)

✅ String extraction (ASCII + UTF-16)

✅ ELF/PE section parsing

✅ YARA rule integration for pattern-based malware detection

✅ JSON export for automation pipelines

✅ Simple GUI frontend + CLI backend

## 📦 Installation

1. Download the latest release
2. Extract the archive:
```bash
unzip REX-v1.0.zip
cd REX
```
3. Run the app:
   For GUI:
   ```bash
    ./REX-v1.0
   ```
   For CLI analysis:
   ```bash
   ./rex_core
   ```
## 🖼️ Screenshots
<img width="1366" height="768" alt="Screenshot_2025-09-20_14_10_01" src="https://github.com/user-attachments/assets/105fd843-c0de-4ab5-9b1c-a2f5239beee6" />

## 📂 Output Example
JSON output:
```bash
{
  "File": "/home/yeabsira/vault",
  "Size": 14584,
  "SHA256": "e5e90f175fe2c3bd736f285b72dcc0dededa2bdbf13c21b98fcc7576b7588f15",
  "Type": "ELF",
  "TypeDetail": "Unix/Linux binary",
  "Entropy": 1.522447,
  "EntropyWindows": [],
  "AsciiStrings": [
    "=/lib64/ld-linux-x86-64.so.2",
    "mgUa",
    "fgets",
    "stdin",...
}
```
## 📖 Usage Scenarios

🔍 Quick triage of suspicious binaries

🧑‍💻 Malware research & training labs

📊 Automated pipelines for static analysis

🎯 Educational projects in reverse engineering

## ⚠️ Disclaimer

This project is for educational and research purposes only.
I am not responsible for misuse of the tool. Always analyze samples in a safe and isolated environment.

## 👨‍💻 Author

Yeabsira Mihret

📌 Mechanical Engineering @ ASTU | Reverse Engineering student @ INSA

 [LinkedIn](https://www.linkedin.com/in/yeabsira-mihret) | [GitHub](https://github.com/yeabsira-mihret)
