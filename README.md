I. Introduction

A cloud server that can encrypt and store the encrypted files that are uploaded by users.
Users are allowed to download the original files whenever they want if they provide the correct public key.

II. Codes

- Template: all .html files
- app.py: functions of upload and download files
- auth.py: sign in, sign up, and sign out
- decrypter.py: all decryption algorithms
- encrypter.py: all encryption algorithms
- divider.py: divide a file into chunks
- models.py: create a database of user's accounts
- restore.py: restore the original file
- tool.py: functions of deletion files
- main.py: run the app
  
III. Libraries

Libraries for encryption and
decryption algorithm
Fernet and Multifernet are used
to encrypt and decrypt private
keys
ChaCha20Poly1305, AESGCM,
AESCCM is used to encrypt and
decrypt parts of a file

IV. Front-end design

![image](https://github.com/thanhtruc0308/Secure-File-Storage-Using-Hybrid-Cryptography/assets/58350349/b51b1b2d-2e01-4fda-9d6f-69737ddc09b5)

Login page

![image](https://github.com/thanhtruc0308/Secure-File-Storage-Using-Hybrid-Cryptography/assets/58350349/86bd594b-b3bc-46a2-9681-2c32e3d961af)

Sign-in page

![image](https://github.com/thanhtruc0308/Secure-File-Storage-Using-Hybrid-Cryptography/assets/58350349/c83f5010-2ad4-4e5a-82c7-2759d5bf69de)

Homepage after login successful
'
![image](https://github.com/thanhtruc0308/Secure-File-Storage-Using-Hybrid-Cryptography/assets/58350349/1a1c79de-a650-4d51-8af2-a780716023cf)

Upload file

![image](https://github.com/thanhtruc0308/Secure-File-Storage-Using-Hybrid-Cryptography/assets/58350349/e29abfa0-cee5-4b7a-a31e-5289b32bb561)

The file is uploaded and encrypted successfully

![image](https://github.com/thanhtruc0308/Secure-File-Storage-Using-Hybrid-Cryptography/assets/58350349/cef109bc-07fe-47ab-86b6-74d72d482cf2)

Downloading the corresponding key

![image](https://github.com/thanhtruc0308/Secure-File-Storage-Using-Hybrid-Cryptography/assets/58350349/25bf47e0-c68c-4ffe-9ede-a70eafcfbb9f)

Restore the file

![image](https://github.com/thanhtruc0308/Secure-File-Storage-Using-Hybrid-Cryptography/assets/58350349/1d35020a-a33a-4f71-84db-c6174cbcc2c8)

Download decrypted file

