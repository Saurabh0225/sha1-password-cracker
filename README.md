# SHA1 Password Cracker (Dictionary Attack)

## 📌 Overview
This project is a Python-based **SHA1 password cracking tool** that demonstrates how
dictionary attacks work by hashing candidate passwords and comparing them with a target
SHA1 hash.

⚠️ **This project is strictly for educational and learning purposes only.**

---

## 🛠️ Technologies Used
- Python 3
- hashlib (built-in Python library)
- Git & GitHub

---

## ⚙️ How the Program Works
1. The user inputs a SHA1 hash
2. The program reads passwords from a wordlist file
3. Each password is hashed using SHA1
4. The generated hash is compared with the target hash
5. If a match is found, the original password is displayed

---

## ▶️ Usage

### Run the program
```bash
python main.py
