# Secure-file-extraction
In this project, the aim is to encrypt and decrypt the files using a private keys.
This program is very important when the data has to be sent confidential and when the data shouldnot be leaked to the third parties.
First step, I am selecting a file named sentence which needs to be encrypted.
Second step, the selected file has some repeated words which can be identified easily, for that I have used functions to generate the stop words.
Third step, the words which have a value greater than 0.014335 are the keywords in the sentence file and are stored seperately.
Fourth step, after generating the keywords and storing them in a file, I used the AES algorithm to encrypt and decrypt the files using the same given private key.
Fifth step, Here I am encrypting both the keywords file and the sentence file.
After the encryption is done, to check the encrypted file is retrived as the same orginal file, we check the decrypted file if it is similar to the orginal file or not.
If decrypted file is similar to the orginal file we can send the private key to the clients so that the data is retrived in a secure way.
