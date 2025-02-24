# Steganography - Secure Data Hiding in Images

## Overview
This project implements **Secure Image Steganography** using the **Least Significant Bit (LSB)** technique. It allows users to securely hide and extract encrypted messages within images, enhancing data privacy and covert communication.

## Features
- **LSB-based Steganography**: Hide text data within image pixels.
- **Encryption with Fernet**: Ensures hidden data remains secure even if extracted.
- **Graphical User Interface (GUI)**: User-friendly interface for embedding and extracting data.
- **Supports Multiple Image Formats**: Works with PNG, JPG, and BMP files.

## Technologies Used
- **Python**
- **Tkinter (GUI)**
- **Cryptography (Fernet Encryption)**
- **PIL (Python Imaging Library)**

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/YOUR_USERNAME/Steganography.git
   cd Steganography
   ```
2. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
1. Run the application:
   ```sh
   python main.py
   ```
2. Select an image and enter the text to hide.
3. Encrypt, embed, extract, and decrypt messages securely.

## Folder Structure
```
Steganography/
│-- main.py  # Main application file
│-- gui.py   # GUI implementation
│-- stegano.py  # Steganography encoding & decoding
│-- encryption.py  # Encryption and decryption logic
│-- assets/  # Images and icons
│-- README.md  # Project documentation
│-- requirements.txt  # Required dependencies
│-- .gitignore  # Ignore unnecessary files
```

## License
This project is licensed under the **MIT License**.

## Contributions
Feel free to contribute by opening an **Issue** or **Pull Request**!

## Contact
For any queries, reach out at **your.email@example.com**.
# Steganography
