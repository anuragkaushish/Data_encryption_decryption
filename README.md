# Data_encryption_decryption

In this project I perfromed data encryption and data decryption using python on a news report word file (data file).
Here I have two Symmetric ciphers (Salsa20, AES (CBC mode)) and two Hash functions (SHA-256, HMAC).
Firstly, I mapped the data of arbitary size to fixed size suing both the Hash functions and got two hash values known as digests.
Secondly, I used two symmetric ciphers for data encryption of data file and got stored those two encrypted files as AES.bin, Salsa.bin files.
Thirdly, I used two symmetric ciphers for data decryption of data file and got stored those two decrypted files as two docx files.
Laslty, for data integrity verification I used same ablove hash functions and created to digests from decrypted docx files and compare both the digests from before encryption and after decryption. If both the digests are same then encryption and decryption was successful otherwise it was a failed encryption and decryption.
