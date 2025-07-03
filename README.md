# 🔐 Pixel Manipulation Image Encryption

A simple Python project that encrypts and decrypts images using pixel-level manipulation. Created as part of the **Prodigy Infotech Internship Program**.

---

## 🧠 How It Works

This tool modifies the RGB values of each pixel in an image using a user-defined numeric key:

- **Encryption**: Adds the key to each pixel's R, G, B values.
- **Decryption**: Subtracts the key to restore the original pixel values.

The formula ensures values wrap using modulo 256, keeping the pixel values valid (0–255).

---

## 🚀 Features

- 🔒 Image encryption using RGB transformation
- 🔓 Decryption restores original image using the same key
- 🖼 Works with JPG/PNG images
- ⚡ Fast and lightweight (uses Python + Pillow)

---

## 💻 Requirements

- Python 3.x
- [Pillow](https://pypi.org/project/Pillow/)

Install Pillow via pip:
```bash
pip install pillow
