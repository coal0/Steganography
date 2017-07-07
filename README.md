# Steganography
A python steganography tool

*DONE* *Main TODO*
1. #DONE# Main funtion to accept argument 
2. #DONE# A function what reads images and writes it to a byte-array
3. #DONE# A Encoder function
4. #DONE# A Decoder function

*Also TODO*
1. #DONE# Encrypt the text
2. #DONE# Add Code to randomize
     + Example -rgb rb # Changes only Red and Blue
     + Example -s 10   # Steps over 10 rbg arr and then changes

*New TODO*
1. #DONE# Add check if image has enough space for the string to hide
2. #DONE# Make code more readable for other programmers PEP-8
3. #DONE# Make more prints for users
4. #DONE# improve seed method
5. #DONE# **MAYBE** Add encryption from file... instead of text in command promt

*Yet Another TODO*
1. #DONE# Fake data
2. #DONE# Rename as suggested
3. Make automated decryptor
4. RSA-BASED-ENCRYPTION/DECRYPTION
5. improve location of files, so we can work with files outside of the current directory
6. complete ./setup
7. refractor usability of the code....
   - A python script that drives the command line tool
   - A module that reads/writes files (although you could probably skip this because it is so simple, and let the command line tool manually read/write files)
   - A module that handles LSB encoding/decoding, and operates on an image array. It should make no attempt at encryption, but simply work with whatever data is passed, whether encrypted or not.
   - A separate module to handle encryption/decryption.
