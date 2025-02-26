# AICTE-Cybersecurity-Project

Secure Data Hiding in Image Using Steganography
This project implements image steganography using Python and OpenCV to securely hide and retrieve secret messages within an image. The encryption process embeds the message at the pixel level, ensuring that the image remains visually unchanged while securely storing the hidden text.

Features:
Message Encryption & Decryption – Hide and retrieve messages from an image.
Password-Protected Access – Only users with the correct passcode can decrypt the message.
Lightweight and Efficient – Uses basic pixel manipulation for fast execution.
Minimal Image Distortion – The message is embedded without significantly altering the image.

Technologies Used:
Python 3
OpenCV (cv2) – For image processing
OS Module – For file handling and execution

How to Run:
Install dependencies:
pip install opencv-python

Run the script:
python stego.py
Enter the secret message and passcode to encrypt the image.
To decrypt, enter the correct passcode to retrieve the hidden message.

Future Improvements:
Enhancing encryption techniques for better security.
Supporting multiple image formats and higher data capacity.
Adding a graphical user interface (GUI) for easier usage.
