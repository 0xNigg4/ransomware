# INFOSEC - RANSOMWARE [Educational]

This project is a **Python-based ransomware simulation** created for **educational purposes only**. It demonstrates how ransomware works, including file encryption and decryption, using modern cryptographic techniques. This project is intended for learning and research in the field of information security.

**Disclaimer**: This tool is for educational use only. Do not use it for malicious purposes. I am not responsible for any misuse of this software.

## Features

- **File Encryption**: Encrypts files using the Fernet symmetric encryption algorithm.
- **File Decryption**: Decrypts files using a user-provided password.
- **Folder Encryption/Decryption**: Recursively encrypts or decrypts all files in a folder.
- **Password Protection**: Uses a password-derived key for encryption and decryption.
- **Hacker Movie Effects**: Includes a matrix-style animation and green text for a "hacker movie" feel.


## Prerequisites

- Python 3.x
- Required Python libraries:
  ```bash
  pip install cryptography
  pip install pyinstaller
  ```
## Usage
1. Clone the Repository
  ```bash
  git clone https://github.com/0xNigg4/ransomware.git
  cd path/ransom.exe
  ```

## Lessons Learned

What did you learn while building this project? What challenges did you face and how did you overcome them?

1. Cryptography Basics
- Understood the importance of key derivation functions like Scrypt for securely generating encryption keys.
2. CLI
- Learned how to make scripts more interactive and accessible.
3. Executable Packaging
- Explored tools like PyInstaller to convert Python scripts into standalone executables.
- Learned how to add custom icons and compress executables using UPX.
4. Challenges Faced
- ANSI Escape Codes: Initially, the colors and animations didn't work in the Windows Command Prompt. I resolved this by enabling ANSI support programmatically.
- Executable Compression: UPX initially failed to compress the executable due to Control Flow Guard (CFG). I used the --force flag to bypass this limitation.
- Antivirus Detection: Some antivirus programs flagged the executable as suspicious. I learned how to handle false positives and exclude files from scans.

### Acknowledgments

- **Cryptography Library**: This project uses the [`cryptography`](https://cryptography.io/) library for secure encryption and decryption.
- **PyInstaller**: Used to convert the Python script into a standalone executable. Learn more at [PyInstaller](https://www.pyinstaller.org/).
- **UPX**: Used for compressing the executable. Check it out at [UPX GitHub](https://upx.github.io/).
- **Python Community**: Thanks to the Python community for providing excellent documentation and resources.

![Logo](https://www.centralinfosec.com/img/central-infosec-shield-black.png)
