# AES (Advanced Encryption Standard)

**Wikipedia:** The Advanced Encryption Standard (AES), also known by its original name Rijndael is a specification for the encryption of electronic data established by the U.S. National Institute of Standards and Technology (NIST) in 2001.


<p align="center">
  <img src= "https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/AES-SubBytes.svg/320px-AES-SubBytes.svg.png"/>
</p>



## Aes.cc  - Implementation of AES with C++ 
These code assumes the block is 128 bit long. The default key is also 128 bits long but this can be changed to 256 or 512 bits. If you want to test a different block of 128 bits, change the values on the Main of the program(variable “block”). 

### Compilation
g++ -std=c++11 -o aes AES.cc 

### Execution
./aes
