# KrypApp
File Encryption GUI App with Python

### Tech Stack
* Python 3
* Tkinter for GUI
* pycryptodomex for Cryptodome
* AES Encryption
* cx_freeze to build executable

### External Dependencies
* `pycryptodomex` for AES encryption.

* `cx_freeze` to build executable.


### To Build Executable


### How to Encrypt/Decrypt
1. Open the App and Click SELECT FILE Button and select your file e.g. "abc.jpg".
2. Enter your Secret Key (This can be any alphanumeric letters). Remember this so you can Decrypt the file later.
3. Click ENCRYPT Button to encrypt. A new encrypted file with ".kryp" extention e.g. "abc.jpg.kryp" will be created in the same directory where the "abc.jpg" is.
4. When you want to Decrypt a file you, will select the file with the ".kryp" extention and Enter your Secret Key which you chose at the time of Encryption. Click DECRYPT Button to decrypt. The decrypted file will be of the same name as before with the suffix "__dekrypted__" e.g. "abc__dekrypted__.jpg".
5. Click RESET Button to reset the input fields and status bar.
6. You can also Click CANCEL Button during Encryption/Decryption to stop the process.

### Credits
> `EncryptionTool` class from [`nsk89`](https://github.com/nsk89) for file encryption.
> `flaticon.com` for icon file.
