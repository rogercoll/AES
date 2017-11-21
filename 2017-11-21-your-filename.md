## AES (Advanced Encryption Standard)

**Wikipedia:** The Advanced Encryption Standard (AES), also known by its original name Rijndael is a specification for the encryption of electronic data established by the U.S. National Institute of Standards and Technology (NIST) in 2001.

![SubBytes function works]({{site.baseurl}}/aes.png)

### Aes.cc

 Implementation of AES with C++. These code assumes the block is 128 bit long and the key too(key can be bigger). If you want to test a different block of 128 bits, change the values in the Main of the program(variable “block”). 

### Compilation

g++ -std=c++11 -o aes AES.cc 

### Execution

./aes









