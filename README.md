# PDF Translation App

This application provides a user-friendly interface to translate the text content of PDF documents from English to German. The translation is powered by the MarianMT model, part of the Hugging Face Transformers library.

## Features

- **PDF Text Extraction**: Extracts text and basic formatting from PDF files.
- **Language Translation**: Translates extracted text from English to German.
- **PDF Generation**: Creates a new PDF with the translated text while maintaining the original layout.
- **Streamlit Interface**: Offers a simple web interface for uploading PDFs and downloading the translated version.

## Installation

To set up the application on your local machine, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/pdf-translation-app.git
   cd pdf-translation-app
   ```

2. **Create a Virtual Enviornment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```