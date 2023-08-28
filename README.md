# QRCodeGeneratorSDK
An SDK to generate QR codes that can link to URLs, text, or other data.

## Overview
This repository contains a simple yet powerful QR Code Generator SDK built in Python. With just a few lines of code, you can generate QR codes right within your own applications. This SDK was designed to be easily integrated into various types of projects, whether you're a beginner in coding or an experienced developer.

## Features
- Easy to install and use
- Customize QR code size and border
- Option to save QR code as an image file
- Written in Python, making it compatible with most systems

## Prerequisites
- Python (Version 3.x is recommended)
- Pip package manager

## Installation
1. **Clone the Repository**
    ```bash
    git clone https://github.com/danielapassos/QRCodeGeneratorSDK.git
    ```
    Navigate to the project folder:
    ```bash
    cd QRCodeGeneratorSDK
    ```
  
2. **Create a Virtual Environment (Optional)**
    ```bash
    python3 -m venv myenv
    ```
    Activate the virtual environment:
    - On Mac/Linux:
        ```bash
        source myenv/bin/activate
        ```
    - On Windows:
        ```cmd
        myenv\Scripts\activate
        ```

3. **Install Required Packages**
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To generate a QR code, simply import the `generate_qr` function and pass in the data you want to encode and the file name where you want to save the QR code.

Example:

```python
from qr_code_sdk import generate_qr

generate_qr("Hello, World!", "hello_world.png")
```

This will generate a QR code with the text "Hello, World!" and save it as an image file named `hello_world.png`.

## Customization
You can easily customize the generated QR code's appearance by modifying the `qr_code_sdk.py` file. Parameters like `version`, `error_correction`, `box_size`, and `border` can be adjusted to fit your needs.

## Contributing
If you find any bugs or would like to contribute new features, feel free to create an issue or make a pull request.

## License
This project is open-source and available under the MIT License.
