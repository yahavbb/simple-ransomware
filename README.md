
# Ransomware Script

## Introduction

This repository contains a simple ransomware script implemented in Python. The script is intended for educational purposes to demonstrate how a ransomware attack works, utilizing AES and RSA encryption techniques to encrypt and decrypt files within a specified directory.

**DISCLAIMER**: This script is provided for educational purposes only and should not be used for any malicious activities. Unauthorized use of this script for harmful or illegal purposes is strictly prohibited.

## Features

- Encrypts and decrypts files using AES and RSA encryption.
- Generates a random AES key for file encryption.
- Encrypts the AES key using an RSA public key.
- Decrypts the AES key using an RSA private key.
- Supports selective encryption based on file extensions.

## Requirements

- Python 3.x
- Required Python packages: `pycryptodome`, `cryptography`

You can install the required packages using the following command:
```bash
pip install pycryptodome cryptography
```

## Usage

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yahavbb/ransomware.git
   ```

2. Run the script using Python:
   ```bash
   python ransomware.py
   ```

3. Choose the mode (`encrypt` or `decrypt`) and provide the necessary parameters:
   - For encryption: Provide a public key (PEM format) or generate one using the `generate_rsa_key_pair()` function in the script.
   - For decryption: Provide the path to the private key (PEM format) used for encryption.

**Note:** The script will recursively encrypt or decrypt files with allowed extensions (defined in the `file_ext_targets` list) within the specified directory.

## Important

- This script is for educational purposes only and should not be used for illegal activities.
- The script's purpose is to illustrate the concepts behind ransomware attacks and to highlight the importance of cybersecurity.
- Using this script for malicious purposes is illegal and unethical.

## Author

This script was created by yahav breslav. Connect with me on [[LinkedIn](https://www.linkedin.com/in/yahav-breslav-bitton/) or [GitHub](https://github.com/yahavbb)].

