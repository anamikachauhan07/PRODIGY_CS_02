# PRODIGY_CS_02: Pixel Manipulation for Image Encryption

# 🖼️ Image Encryption Tool

A Python-based image encryption and decryption tool that uses pixel manipulation techniques to secure image files. The application applies a mathematical XOR operation to each pixel value using a user-defined secret key, allowing users to encrypt and decrypt images while preserving image integrity.

This project was developed as part of the **Prodigy Infotech Cyber Security Internship (Task 02)**.

## 🚀 Features

- Encrypt image files using pixel-level XOR manipulation
- Decrypt encrypted images using the same secret key
- Supports RGB and RGBA images
- Preserves image quality and transparency
- Simple command-line interface
- Fast and lightweight implementation

## 🛠️ Technologies Used

- Python 3
- Pillow (PIL)

## 📂 Project Structure

PRODIGY_CS_02/
│
├── image_encryption.py
├── ima.jpg
├── encrypted.png
├── recovered.jpg
└── README.md


## ⚙️ How It Works

The program encrypts every pixel using the XOR operation.

encrypted_pixel = original_pixel ^ secret_key

Since XOR is reversible:

decrypted_pixel = encrypted_pixel ^ secret_key

Using the same secret key restores the original image.

## 📦 Installation

### Clone the Repository

git clone https://github.com/anamikachauhan07/PRODIGY_CS_02.git
cd PRODIGY_CS_02

### Install Dependencies

pip install pillow

## ▶️ Usage

Run the program:

python image_encryption.py

## 🔐 Encryption Process

1. Load the image.
2. Read each pixel.
3. Apply XOR using the secret key.
4. Save the encrypted image.
5. Use the same key to decrypt and recover the original image.

## 📸 Supported Image Formats

- PNG
- JPG / JPEG
- BMP
- Any image format supported by Pillow

## 🧪 Example Workflow

### Encryption

Original Image
       │
       ▼
 XOR Secret Key
       │
       ▼
Encrypted Image

### Decryption

Encrypted Image
       │
       ▼
Same Secret Key
       │
       ▼
Recovered Image

## 🎯 Learning Objectives

This project demonstrates:

- Image Processing
- Pixel Manipulation
- XOR Encryption
- File Handling in Python
- Basic Cryptography Concepts
- Command-Line Application Development

## 👩‍💻 Author

**Anamika Chauhan**

Cyber Security Intern – Prodigy Infotech

GitHub: https://github.com/anamikachauhan07

## 📜 License

This project is created for educational purposes as part of the **Prodigy Infotech Cyber Security Internship (Task 02)**.
