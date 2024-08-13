Here's how the program works:

The caesar_encrypt function takes a message and a shift value as input, and returns the encrypted message. It iterates through each character in the message, and if the character is a letter, it shifts it by the specified amount using the ASCII values of the characters.
The caesar_decrypt function is similar to caesar_encrypt, but it shifts the characters in the opposite direction to decrypt the message.
The main function is the entry point of the program. It presents a menu to the user, allowing them to choose between encrypting a message, decrypting a message, or quitting the program.
If the user chooses to encrypt or decrypt a message, they are prompted to enter the message and shift value. The program then calls the appropriate function (caesar_encrypt or caesar_decrypt) and prints the result.
