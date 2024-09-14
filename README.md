# PDF-WORD CONVERTER
A web application for converting PDF documents to Word (.docx) files and vice versa. This project provides an easy-to-use interface for users to upload files and perform conversions between these two popular document formats.

## Features

- Convert PDF files to Word (.docx) format.
- Convert Word (.docx) files to PDF format.
- Simple and intuitive web interface.
- Responsive design for mobile and desktop users.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask/Django) or Node.js (Express)
- **Conversion Libraries**:
  - `pdf2docx` for PDF to Word conversion
  - `docx2pdf` for Word to PDF conversion

## Installation

### Prerequisites

- Python 3.x or Node.js
- Virtual environment (for Python)
- Pip or npm (for package management)

### Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/username/repository.git
   cd repository

2. **Install dependencies:**

- For Python (using requirements.txt):
  ```bash
  python -m venv venv
  source venv/bin/activate  # On Windows use `venv\Scripts\activate`
  pip install -r requirements.txt


3. **Run the application:**
   ```bash
   python app.py  # or `python manage.py runserver` for Django


3. **Open your browser and navigate to:**
   ```bash
   http://localhost:5000/

## Usage
1. Convert PDF to Word:

- Click the "Upload PDF" button to upload your PDF file.
- Click "Convert to Word" to start the conversion process.
- Download the resulting Word file from the link provided.

2. Convert Word to PDF:
- Click the "Upload Word" button to upload your Word file.
- Click "Convert to PDF" to start the conversion process.
- Download the resulting PDF file from the link provided.

# License
This project is licensed under the MIT License. See the LICENSE file for more details.
