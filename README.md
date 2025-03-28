# Mistral OCR Tool

This Python program allows you to select a PDF file, send it to Mistral's OCR API for text and image extraction, and save the resulting processed PDF file to a location of your choice.

## Features
- Select a PDF file using a graphical file dialog.
- Upload the PDF to Mistral's OCR API for processing.
- Save the processed PDF file to a specified location.

## Prerequisites
- Python 3.7 or higher
- An API key for Mistral's OCR API

## Installation

1. Clone this repository or download the files to your local machine.

2. Navigate to the project directory:
   ```bash
   cd path/to/Mistral_OCR
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set the `MISTRAL_API_KEY` environment variable with your Mistral API key. On Windows, you can do this by running:
   ```bash
   set MISTRAL_API_KEY=your_api_key_here
   ```

## Usage

1. Run the program:
   ```bash
   python mistral_ocr_tool.py
   ```

2. A file dialog will appear. Select the PDF file you want to process.

3. The program will upload the file to Mistral's OCR API and process it.

4. Another file dialog will appear, allowing you to choose where to save the processed PDF file.

## Notes
- Ensure that your PDF file meets the size and page limits specified by Mistral's OCR API (e.g., max 50 MB and 1,000 pages).
- The program uses the `mistralai` library to interact with the API.

## License
This project is licensed under the MIT License.