# rawaes


rawaes encrypts a file using the Advandced Encryption Standard (AES).  AES uses the Rijndael Algorithm, a 128-bit block cipher, to encrypt.  Since the encryption requires 16-byte blocks, rawaes will pad any uneven blocks with 0s, possibly increasing the size of the file upto 15 bytes.

to build:

haiku

cd to the rawaes directory

make


BeOS

Doubleclick rawaes.proj and build from BeIDE.