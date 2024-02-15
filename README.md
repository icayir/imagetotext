# Image to Text Converter Web Application

### Overview
This web application is designed to convert text from images into plain text. It utilizes Python, Flask, and PyTesseract to achieve this functionality.

### Prerequisites
Before running the application, ensure that you have the following installed on your computer:

Python (3.6 or higher)

Virtual Environment (venv)

### Setting up Virtual Environment (venv)
Open a terminal window.

Navigate to the project directory.

Create a virtual environment using the following command:

python -m venv venv


Activate the virtual environment:

On Windows:

.\venv\Scripts\activate

On Linux: 

source venv/bin/activate

### Installing Dependencies
Once the virtual environment is activated, install the required dependencies using the following commands:

pip install flask

pip install pytesseract

Make sure you have Tesseract OCR installed on your machine. You can download it from https://github.com/tesseract-ocr/tesseract

### Running the Application
After setting up the virtual environment and installing the dependencies, you can run the application with the following command:

python app.py

The application will be accessible at http://127.0.0.1:5000/ in your web browser.











