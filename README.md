 # Caesar Cipher Tool

A Python-based tool for encrypting and decrypting messages using the Caesar Cipher technique. This project also includes a message analyzer to provide insights into the structure of the input message.

## Features

- **Encrypt Messages**: Securely encrypt messages using a shift-based Caesar Cipher.
- **Decrypt Messages**: Decrypt previously encrypted messages using the same shift value.
- **Message Analysis**: Analyze the input message for character composition (letters, digits, special characters).
- **Invisible Input**: Uses `getpass` to hide sensitive inputs like the message and shift value.

## How It Works

The Caesar Cipher shifts each letter in the message by a specified number of positions in the alphabet. Non-alphabetic characters remain unchanged.

### Encryption
- Each letter is shifted forward by the specified shift value.
- Example: With a shift of 3, `A` becomes `D`, `B` becomes `E`, and so on.

### Decryption
- Each letter is shifted backward by the specified shift value.
- Example: With a shift of 3, `D` becomes `A`, `E` becomes `B`, and so on.

## Example for Encryption
------------------------------------- Caesar Cipher Tool -------------------------------------

Do you want to encrypt or decrypt a message? Input 'e' for encryption, 'd' for decryption, or 'q' to quit: e
Enter the message (invisible, type carefully): [hidden]
Please check whether the message you provided was correct or not using the following hints:

First and last characters of the message: H***o
Total number of characters entered: 5
Number of alphabetical letters: 5
Number of digits: 0
No special characters in the message.
Enter the shift value (invisible, type carefully): [hidden]

Encrypted Message: Khoor

## Example for Decryption
------------------------------------- Caesar Cipher Tool -------------------------------------

Do you want to encrypt or decrypt a message? Input 'e' for encryption, 'd' for decryption, or 'q' to quit: d
Enter the message (invisible, type carefully): [hidden]
Please check whether the message you provided was correct or not using the following hints:

First and last characters of the message: K***r
Total number of characters entered: 5
Number of alphabetical letters: 5
Number of digits: 0
No special characters in the message.
Enter the shift value (invisible, type carefully): [hidden]

Decrypted Message: Hello
