# ConvertEase 🚀

**Seamless conversions, anytime.**  

ConvertEase is an all-in-one file conversion web application that simplifies converting your documents, images, and presentations. With a sleek, modern UI and powerful backend functionality, ConvertEase lets you transform your files with just a few clicks.

---

## Features ✨

- **📷 JPG to PDF:** Convert image files (JPG, JPEG, PNG) into high-quality PDFs.  
- **📄 PDF to JPG:** Extract pages from PDFs and save them as JPG images.  
- **📑 PPT to PDF:** Convert PowerPoint presentations to PDF using LibreOffice.  
- **📝 Word to PDF:** Transform Word documents (DOC/DOCX) into PDFs.  
- **📊 Excel to PDF:** Convert Excel spreadsheets (XLS/XLSX) into PDFs.  
- **🔎 PDF OCR:** Extract text from scanned PDFs using Tesseract OCR.  
- **✍️ PDF to Word:** Convert PDFs into editable Word documents.  
- **🖼️ PDF to PPT:** Convert PDFs into editable PowerPoint presentations.

---

## Technologies Used 🛠️

- **Python & Flask**  
- **HTML, CSS & JavaScript**  
- **Pillow** – Image processing  
- **pdf2image** – Converting PDF pages to images  
- **Tesseract OCR** – Optical Character Recognition  
- **Poppler** – PDF rendering  
- **LibreOffice** – Document conversion  
- **Ghostscript** – PDF compression (if used)

---

## Installation & Setup 📦

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/ConvertEase.git
   cd ConvertEase
2. **Create & Activate a Virtual Environment**
Windows:
  ```bash
  python -m venv venv
  venv\Scripts\activate
3. **Install Python Dependencies**
  ```bash
  pip install -r requirements.txt
4. **Install External Tools & Update Paths**
Poppler:
Download Poppler for Windows, extract it, and update the poppler_path variable in app.py.
Tesseract OCR:
Download Tesseract OCR and ensure it’s installed at:
C:\Program Files\Tesseract-OCR\tesseract.exe
(This path is set in app.py.)
LibreOffice:
Download LibreOffice and update the libreoffice_path in app.py if necessary.
Ghostscript:
Download Ghostscript and ensure gswin64c.exe is in your system PATH if you plan to use PDF compression.

