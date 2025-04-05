# MSFvenom Shellcode Examples (MessageBox & Calc)

This repository provides ready-to-use MSFvenom shellcode for common Windows payloads, such as displaying a MessageBox or launching `calc.exe`.  
It is intended for testing, research, and education in exploit development or shellcode injection.

---

## 📦 Included Shellcode

### ✅ MessageBox (x86 / x64)
- Displays a simple Windows MessageBox with custom text.
- Generated with MSFvenom using `windows/messagebox`

### ✅ Exec Calc (x86 / x64)
- Executes `calc.exe` on the target system.
- Generated using `windows/exec CMD=calc.exe`

---

## 🛠 Usage

These shellcodes can be used for:

- Learning shellcode structure
- Practicing injection techniques (C, C++)
- Malware analysis training
- Shellcode AV evasion experiments

---

## 💻 Example Output

```msfvenom -p windows/messagebox TEXT="Hello from shellcode" -f c msfvenom -p windows/exec CMD=calc.exe -f c```

---

## 📂 Shellcode Formats

- C-style arrays
- Raw binary

---

## 🔍 Keywords for Search Engines

msfvenom messagebox shellcode, windows shellcode example, calc shellcode msfvenom, windows exec shellcode, generate shellcode with metasploit, shellcode to open messagebox, msfvenom calc payload, metasploit windows examples

---

## ⚠️ Disclaimer

This repository is for **educational and research** purposes only.  
Do not use these techniques on systems without **explicit permission**.
