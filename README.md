#**Image Steganography - Hide Messages in Images**


**Overview**

This project implements image steganography, a technique that embeds a secret message within an image using pixel manipulation. The message is encrypted into the image and can only be extracted using a password, ensuring secure and covert communication.

**Features**

✅ Invisible Message Embedding – The image looks unchanged to the human eye.

✅ Password-Protected Decryption – Only authorized users can extract the message.

✅ Lightweight & Efficient – Uses basic Python libraries for seamless execution.

✅ No External Tools Required – Works within a simple Python environment.

**Technology Used**

**Programming Language:** Python

**Libraries:** OpenCV, NumPy

**Platform:** Google Colab / Jupyter Notebook

**How It Works :** 

**Encryption:**
The user enters a secret message and a password.
The message is embedded into the image using pixel modification.
The encrypted image is saved and displayed.

**Decryption:**
The user provides the password to retrieve the hidden message.
The message is extracted from the image pixels.
