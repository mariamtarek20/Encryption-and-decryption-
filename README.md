Encryption and Decryption Tool
This Python script provides a simple graphical user interface (GUI) for text encryption and decryption using a basic substitution cipher. The script uses the Tkinter library for the GUI components.

How to Use:
Encrypting Text:

Enter the text you want to encrypt in the "Enter text to encrypt" entry field.
Click the "Encrypt" button.
The encrypted text will appear in the "Enter text to decrypt" entry field.
Decrypting Text:

Enter the encrypted text in the "Enter text to decrypt" entry field.
Click the "Decrypt" button.
The decrypted text will appear in the "Enter text to encrypt" entry field.
Substitution Cipher Algorithm:
Encryption:

Each alphabetical character in the input is shifted by 11 positions to the right in the alphabet (wrapping around if necessary).
Non-alphabetic characters remain unchanged.
Decryption:

The encrypted numbers are shifted back by 11 positions to the left in the alphabet to reveal the original characters.
Non-alphabetic characters remain unchanged.
Example:
Encrypt:

Input: "hello world"
Output: "21 4 8 11 14 14 26 4 17 11 19"
Decrypt:

Input: "21 4 8 11 14 14 26 4 17 11 19"
Output: "hello world"
How to Run the Script:
Ensure you have Python installed on your system.
Run the script by executing the command: python script_name.py in your terminal or command prompt.
Dependencies:
This script requires the tkinter library, which is included in standard Python installations.
Notes:
This script is a basic example and should not be used for secure encryption purposes.
Feel free to modify and enhance the code for more advanced encryption algorithms or additional features.
Author:
[Mariam Tarek]

Version:
1.0.0 (Insert version number if applicable)

Acknowledgments:
The script is a simple demonstration and may not be suitable for production use.
Tkinter documentation: https://docs.python.org/3/library/tkinter.html