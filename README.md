# FileEncrypption_and_Decryption
# File Encryption and Decryption

This project implements a simple file encryption and decryption mechanism using the Caesar cipher technique. The Caesar cipher shifts the value of characters to encode and decode the content of files. This project is written in C++.

## Features

- Encrypts the content of a file using the Caesar cipher.
- Decrypts the encrypted file back to its original content.
- Creates a new file for the encrypted content.

## Requirements

- A C++ compiler (e.g., g++, clang++)
- Standard C++ library

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/file-encryption-decryption.git
    cd file-encryption-decryption
    ```

2. Compile the source code:
    ```bash
    g++ -o file-encryption-decryption main.cpp
    ```

## Usage

1. To encrypt a file:
    ```bash
    ./file-encryption-decryption encrypt input.txt encrypted.txt shift_value
    ```
    - `input.txt`: The file you want to encrypt.
    - `encrypted.txt`: The output file where the encrypted content will be saved.
    - `shift_value`: The integer value by which the characters in the file will be shifted.

2. To decrypt a file:
    ```bash
    ./file-encryption-decryption decrypt encrypted.txt decrypted.txt shift_value
    ```
    - `encrypted.txt`: The file you want to decrypt.
    - `decrypted.txt`: The output file where the decrypted content will be saved.
    - `shift_value`: The integer value by which the characters in the file were originally shifted.

## Example

To encrypt a file `example.txt` with a shift value of 3:
```bash
./file-encryption-decryption encrypt example.txt encrypted_example.txt 3
