# csce-548-project
Task 1: Encryption using OpenSSL commands with different cipher and mode options
----------------------------------------------------------------------------------------------------------------
A.	 Mode 1 using CBC 
1.	Encryption 
-	openssl enc -des-ede-cbc -e -in plain.txt -out cipherbin.bin -k password  
       this command encrypts a text file with CBC mode and with a password

this is the plain text file:  using command 
vim plain.txt

![filename](https://user-images.githubusercontent.com/36014195/36122343-010222b0-1017-11e8-9638-2e634287750f.png)

   this is what the encrypted file looks like: using command vim cipherbin.bin
   ![screen shot 2018-02-12 at 4 40 41 pm](https://user-images.githubusercontent.com/36014195/36122546-be277d4a-1017-11e8-8520-acf3a9d22a6a.png)

2.	Decryption
-	openssl enc -des-ede-cbc -d -in cipherbin.bin -out cipherout.txt -k password
this command decrypts bin file with CBC mode and passed in the password

this is what decrypted file looks like: using command vim cipherout.txt
![screen shot 2018-02-12 at 4 46 37 pm](https://user-images.githubusercontent.com/36014195/36122563-d7567e6a-1017-11e8-970c-3f8bff4e66e8.png)

