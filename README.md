# URL to QR Code Generator
This is a simple Node.js script that generates a QR code from a URL entered by the user. The QR code is saved as an image file, and the URL itself is stored in a text file.

## Features
Interactive Prompt: The user is prompted to input a URL via the terminal.
QR Code Generation: A QR code for the provided URL is generated and saved as an image (qr_img.png).
URL Storage: The provided URL is also saved in a text file (URL.txt).
Technologies Used
Node.js: Runtime environment for executing JavaScript on the server.
Inquirer: A Node.js module for creating interactive prompts in the terminal.
qr-image: A module for generating QR codes from strings.
fs: The Node.js File System module for reading and writing files.
How It Works
The user is prompted to enter a URL in the terminal.
The script generates a QR code for the URL and saves it as an image file (qr_img.png).
The URL is saved to a text file (URL.txt).
Upon successful completion, a confirmation message is displayed in the console.
How to Run the Project

Clone this repository:

```git clone https://github.com/your-username/repository-name.git```

Install the required dependencies:

```npm install```

Run the script:

```node script.js```

Follow the prompt to input a URL. The QR code will be saved as qr_img.png, and the URL will be saved as URL.txt.

```$ node script.js```

Type in your URL: https://www.example.com

### This will generate:
qr_img.png: The QR code image.

URL.txt: The file containing the URL https://www.example.com.

### Dependencies
inquirer: ^8.0.0

qr-image: ^3.2.0

fs: Built-in Node.js module
