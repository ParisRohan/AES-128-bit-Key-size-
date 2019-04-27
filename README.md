# AES-128-bit-Key-size
Implementation of AES algorithm using 128 bit key size in java

AES is acronym for "Advanced Encryption Standard".

It is more secure than DES and uses public-key cryptography.

AES uses 128bit,192bit,256bit keys for encryption.

Number of rounds of encryption/decryption in AES depends on key size as follows:-
      KEY size  -  Rounds,
      128       -   10,
      192       -   12,
      256       -   14,

The key is passed through Key-expansion algorithm to generate more words. A word in AES is a column of key-matrix

Following procedure are carried in each round:-
      1)Substitute from s-box
      2)Row shift
      3)Column transpose
      4)Addition of round key
      
Steps of AES:-
             Plain text
                  |
             Initial Permutation
                  |
             Rounds depending on key size
                  |
             Cipher text 
