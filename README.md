# Encrypt/Decrypt in C

## About
This program (designed in C) allows you to encrypt and decrypt .txt files.
*Not included in this version: Allowing the program to also encrypt and decrypt your passwords, similar to Google's "suggested password" feature via a non-random pattern, except that if you forget your encrypted password, you can encrypt for the same value, or find out the original password you had intended via decryption.

## How To
### Encryption
**Make sure to save the file you wish to encrypt elsewhere if you are likely to lose your password. Unable to recover original content once you forget the password.**
1. Type the name of the file you wish to encrypt. (*Note*: File must be in .txt format and located within the same file as the program.)
1. Enter a 2-8 letter/digit password to encrypt the document. (You will need this same password to later decrypt the document.)
1. Hash code value will be produced as a way to verify whether the password you input is correct or not.
1. Voila! Your document has been encrypted. **PERMANENTLY**

### Decryption
2. Type the name of the file you wish to decrypt. (*Note*: File must be in .txt format and located within the same file as the program.)
2. Enter a 2-8 letter/digit password to decrypt the document.
2. The program will check the original hash code with the encrypt-version hash code to verify that this is indeed the right password.
2. Voila! Your document has been decrypted. Restart program to encrypt again!

## Notes
* The program file will only run on Windows, as it is a .exe file.
* The code was written on Code::Blocks IDE. Running the code on this IDE will allow you to run successfully.
