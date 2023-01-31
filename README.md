# Secret Message Encryption Game
## Honey Encryption or HoneyTrap

This code contains a game that encrypts a secret message entered by the user. It uses a password and a random seed value to generate a cipher text.

## How it works
1. The user is prompted to enter a password and a secret message to be encrypted.

2. A random seed value is generated and the password is manipulated to create multiple seed-message pairs.

3. The encryption process involves XOR operation between the password-seed pair and the true seed value.

4. The password-seed pairs and the secret messages are stored in two dictionaries passwordsToSeeds and seedsToMessages respectively.

5. The generated cipher text, password-seed pairs and secret messages are displayed to the user to begin the game.

6. The user can then attempt to decrypt the cipher text by entering a password. If the entered password is in the passwordsToSeeds dictionary, the corresponding seed value is obtained, XORed with the cipher text to obtain the original secret message.

7. The user has the option to encrypt another secret message.

## Note
The secret messages are limited to one-word U.S states as specified in the states dictionary.
The user password and seed value should be entered in the same case as they were entered during the encryption process.
## Conclusion
The Secret Message Encryption Game is a fun way to explore the concept of encryption and decryption. Feel free to modify the code to customize the game and make it more challenging.
