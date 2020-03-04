# ocr_extract
ocr program to extract information form pdf, png, jpg, tiff files.

# Geting Started:

1. Tesseract is a wrapper for Google's Tesseract Egnine, download Tesseract-OCR for windows: 
https://github.com/UB-Mannheim/tesseract/wiki
after download the Tesseract, locate the path as:
pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract'

2. Wand package is required, wand is a package binding with ImageMagick, install ImageMagick on Windows: https://legacy.imagemagick.org/script/download.php#windows
Wand also requires Ghostscript to scanning pdf file. To install Ghostscript, simply follow the link:
https://www.ghostscript.com/download.html

3. Spacy package is involed in this program, to install Spacy, simply do 'pip install spacy'.
After install Spacy, you need to install English model for Spacy, simply do 'python -m spacy download en_core_web_sm'.
