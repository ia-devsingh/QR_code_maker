# QR Code Maker

A simple Python project that generates a QR code image from a text string or website URL.

## Features
- Prompts the user to enter text or a URL
- Creates a QR code image from the input
- Saves the QR code as `my_qr_code.png`

## Requirements

Install the Python package below before running the script:

```bash
pip install qrcode[pil]
```

## Usage

```bash
python QR_code_maker
```

Then enter any text or website URL when prompted. The script will create a file named:

```text
my_qr_code.png
```

## Example

```text
Enter text or a website URL: https://github.com
```

This will generate a QR code for the GitHub URL.

## Project Files

- `qr_maker.py` — main script that creates the QR code

## Notes

This project is intentionally simple and beginner-friendly for learning how to generate QR codes in Python.
