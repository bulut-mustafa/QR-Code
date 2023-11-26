# Project Title

This is a simple Node.js application that generates a QR code from a user-provided URL.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You need to have Node.js and npm installed on your machine. 

### Installing

1. Clone the repository
2. Navigate to the project directory
3. Run `npm install` to install the dependencies

## Usage

1. Run the application using `node index.js`
2. You will be prompted to enter a URL. Type in your URL and press Enter.
3. The application will generate a QR code for the provided URL and save it as `qr_img.png` in the project directory.
4. The URL will also be saved in a text file named `URL.txt`.

## Built With

- [Node.js](https://nodejs.org/)
- [Inquirer.js](https://www.npmjs.com/package/inquirer) - A collection of common interactive command line user interfaces.
- [qr-image](https://www.npmjs.com/package/qr-image) - A module to generate QR codes.




## Next Steps

- Improve error handling
- Add more customization options for the QR code generation