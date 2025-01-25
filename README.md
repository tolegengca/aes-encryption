# AES-256 Encryption System

[![Python Version](https://img.shields.io/badge/python-3.7%2B-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Secure implementation of AES-256 in CBC mode with PKCS7 padding for sensitive data protection.

## Features
- 🔐 AES-256 encryption/decryption
- 🔑 Automatic key generation
- 📦 Base64 encoding for safe data transfer
- 📝 PKCS7 padding support

## Installation
```bash
git clone https://github.com/yourusername/aes-encryption.git
cd aes-encryption
pip install -r requirements.txt
```

## Usage
```python
from src.aes_crypto import AESEncryptor

# Initialize with auto-generated key
encryptor = AESEncryptor()

# Encrypt data
encrypted = encryptor.encrypt("Secret message")

# Decrypt data
decrypted = encryptor.decrypt(encrypted)
```

## Example Output
```
Encrypted: MDAwMDAwMDAwMDAwMDAwMOexh1B5jHh6Xj7S...
Decrypted: Secret message
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first.

## License
[MIT](https://choosealicense.com/licenses/mit/)
