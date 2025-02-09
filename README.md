# About YBV QR Encode Decode

![Icon](./icons/icon128.png)

YBV QR Encode Decode is a chrome web extension which can help you to decrypt QR data when you will provide with the password and then the number of iterations.


### Algorithum Under the hood
PBEWithMD5AndDES (Password-Based Encryption with MD5 and DES) is an encryption mechanism that:

Derives a cryptographic key and initialization vector (IV) from a password and salt using an iterative MD5 hashing process.
Enhances security by adding a salt (random data) and repeating the hash operation multiple times (iterations) to slow down brute-force attacks.
Uses DES (Data Encryption Standard) to encrypt or decrypt data in CBC (Cipher Block Chaining) mode with the derived key and IV.
Incorporates PKCS#7 padding to handle data that doesn't fit the block size required by DES.
Is considered outdated due to DES's limited security (56-bit key size) and has been largely replaced by stronger algorithms like AES.


### Extension Link
![Icon](./publishing%20extension/publishedss.png)
| ![Icon](./publishing%20extension/md1.png) | ![Icon](./publishing%20extension/md2.png) |
|:------------------------------------------:|:------------------------------------------:|

[Click here to check our extension...](https://chromewebstore.google.com/detail/ybv-qr-encoder-decoder/bkfdepagfbledopemnbibcpcmainlfam)