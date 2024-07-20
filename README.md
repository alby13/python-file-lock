# 🔒Python File Lock

Quantum-Resistant 4-Layer Encryption Program

[![Python Version](https://img.shields.io/badge/python-3.10%2B-blue)](https://www.python.org/downloads/)

## 📖 Introduction

Python File Lock is a Free for individuals, technologically advanced, readable source code, File Encryption and Decryption Software designed to provide exceptional Quantum-resistant security for personal data. Utilizing a unique 4-layer Multi-Encryption approach with password HMAC hashing and PBKDF2 deriving, this program offers resistance against attacks from both current and future supercomputers and quantum computers.

Whitepaper:
<center><a href="https://github.com/alby13/python-file-lock/blob/main/python-file-lock-whitepaper-v2.pdf"><img src="https://github.com/alby13/python-file-lock/blob/main/thumbnail-whitepaper.png"></a></center>

### 🔑 Key Features

- 4-layer encryption: Fernet, AES-256-CBC, ChaCha20-Poly1305, and XOR
- Quantum-resistant encryption engine
- Straightforward user interface
- Automatic encryption and decryption process
- Viewable-source (with restrictions, see License)

# ❓How to use:
<img src="https://github.com/alby13/python-file-lock/blob/main/image-program-screen.png">

### Launch the program


<code>python_file_lock.py</code>

If you are using Windows, you may launch the file with the Batch (BAT) File by double clicking on **RunPythonFileLock.bat**

Inspired by legacy programs, the program begins by asking you if you want to clear the text on your screen to display the program menu wizard from the top of the screen. Select Yes by typing "y" and pressing enter, or select No by typing "n" and pressing enter.

### Select Encrypt or Decrypt

- Do you want to Encrypt or Decrypt? Select Encrypt by typing "E" or "e"

  The program will automatically process the file and output the result and output it as {Program Name}.encrypt

Password Recommendations
You may use any password that you wish, but using a weak password will make your encrypted file weak. You may create a strong password by using Lowercase, Uppercase, Numbers, and Symbols and also use a long password with over 12 characters. For generating a strong password, we recommend generating a password using KeePass, an open-source password generator and password manager. KeePass can generate high-entropy passwords that significantly enhance the security of your encrypted files.

Security
Python File Lock uses a combination of strong encryption algorithms and a multi-layer approach to provide robust security:

Fernet (AES-128-CBC with HMAC-SHA256)
AES-256-CBC
ChaCha20-Poly1305
XOR with a random key

This combination is designed to resist attacks from current supercomputers and remain secure against potential quantum computer attacks in the future.

# Limitations
- Remember that the security of your encrypted files ultimately depends on the strength of your password. Always use a strong, unique password for each encrypted file.
Contributing
- While we appreciate interest in the project, we are not accepting code contributions at this time due to licensing restrictions. However, we welcome bug reports and feature suggestions through the Issues tab.
  
# License
Python File Lock is released under a dual license:

- For individuals, non-profits, and educational institutions: Free to download, use, and review the code. You may not develop your own program based on this code.
- For companies and other organizations: A commercial "Pro" version is available for purchase.

Please see the LICENSE.txt file for full details.

# Disclaimer
This software is provided "as is", without warranty of any kind. Use at your own risk.

Proudly Programmed and Made In The USA.
