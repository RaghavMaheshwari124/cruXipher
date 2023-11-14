# Anor Londo Unveiled
- We are given a dump.zip file which on inspection turned out to be a firefox dump.
- Inside the version folder we find a logins.json file which had encrypted usernames as well as passwords alogn with a key4.db file.
- https://github.com/unode/firefox_decrypt provides a tool to decrypt these encrypted values.
- On decryption we get a Base64 encoded string in the password values 'Z2FtZW92ZXI=' which in ASCII is gameover.


## Flag
```
cruXipher{gameover}
```
