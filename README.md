# Secure Password Generator

A simple and secure password generator built using Python.  
This project generates strong random passwords with customizable options like uppercase letters, lowercase letters, digits, and symbols.

---

# Features

- Generate secure random passwords
- Choose password length
- Include:
  - Uppercase letters
  - Lowercase letters
  - Digits
  - Symbols
- Stores generated passwords in a file
- Uses Python `secrets` module for security
- Command-line based application

---

# Technologies Used

- Python
- argparse
- secrets
- string

---

# Project Structure

```bash
password_generator.py
passwordlist.txt
README.md
```

---

# Installation

## Clone the Repository

```bash
git clone https://github.com/your-username/password-generator.git
```

## Navigate to Project Folder

```bash
cd password-generator
```

---

# How to Run

## Basic Command

```bash
python password_generator.py --upper --lower --digits --symbols
```

---

# Command-Line Arguments

| Argument | Description |
|---|---|
| `-l` or `--length` | Password length |
| `--upper` | Include uppercase letters |
| `--lower` | Include lowercase letters |
| `--digits` | Include digits |
| `--symbols` | Include symbols |

---

# Example Commands

## Generate 12-character password

```bash
python password_generator.py --upper --lower --digits
```

---

## Generate 20-character strong password

```bash
python password_generator.py -l 20 --upper --lower --digits --symbols
```

---

# Example Output

```bash
Generated Password: A9@kLm2#Qx1P
Password saved to passwordlist.txt.
```

---

# How It Works

1. User provides options through command-line arguments.
2. Program creates a character pool.
3. Secure random characters are selected using Python's `secrets` module.
4. Password is generated.
5. Password is saved into `passwordlist.txt`.

---

# Security Features

- Uses cryptographically secure random generation
- Excludes unsafe special characters
- Supports strong password combinations

---

# Why `secrets` Module?

The `secrets` module is designed for:
- Password generation
- Authentication systems
- Security-related applications

It is more secure than Python's `random` module.

---

# Future Improvements

- GUI version
- Password strength checker
- Clipboard support
- Encrypted password storage
- Password history management

---

# Sample Code Flow

```python
password = generate_password(
    args.length,
    args.upper,
    args.lower,
    args.digits,
    args.symbols
)
```

---

# Author

Venkatesh Adusumalli

---

# License

This project is open-source and available under the MIT License.
