# Captcha Solver Demo

## Summary
The Captcha Solver Demo is a small web application designed to demonstrate the capabilities of Optical Character Recognition (OCR) using Tesseract.js to solve captchas. This project showcases how machine learning can be utilized to automatically interpret text within images.

## Setup

### Prerequisites
- Node.js (version 12 or higher)
- NPM (Node Package Manager)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/captcha-solver-demo.git
   ```
2. Navigate to the project directory:
   ```bash
   cd captcha-solver-demo
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```

## Usage
1. Start the application:
   ```bash
   npm start
   ```
2. Open your browser and navigate to `http://localhost:3000`.
3. To solve a captcha image, append the image URL as a query parameter in the URL:
   ```
   http://localhost:3000?url=<image>
   ```
   Replace `<image>` with the direct URL of the captcha image.

## Test Instructions
To test the captcha solving feature, visit the following URL format in your browser:
```
http://localhost:3000?url=<image>
```
For example:
```
http://localhost:3000?url=https://example.com/path/to/captcha.png
```

## Attachments Location
All image files and additional resources used for testing are located in the `assets/` directory.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details. 

---

This README provides an overview of the Captcha Solver Demo, its setup, usage instructions, testing, and licensing details for users and developers. Happy coding!