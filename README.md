# QRGenerator

A simple Python-based QR code generator that creates and saves QR codes as PNG files.

## Features

- Generate QR codes from any text or link
- Save QR codes as PNG images
- Easy-to-use command-line interface

## Requirements

- Python 3.6 or higher
- [qrcode](https://pypi.org/project/qrcode/) Python library

## Installation

1. Clone this repository or download the source code.
2. Install the required dependencies using the provided requirements file:

   ```powershell
   pip install -r requirements.txt
   ```

## Usage

Run the script using Python:

```powershell
python main.py
```

You will be prompted to enter:

- The data to encode in the QR code (e.g., a URL or any text)
- The filename to save the QR code image (e.g., `qr_code.png`)

## Example

```powershell
Enter the data to encode in the QR code: https://example.com
Enter the filename to save the QR code (e.g., qr_code.png): my_qr.png
```

This will generate a QR code for `https://example.com` and save it as `my_qr.png` in the current directory.

## License

This project is licensed under the MIT License.
