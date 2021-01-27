# ocr_extract
ocr program to extract information from pdf, png, jpg, tiff files.

# Geting Started:

1. Tesseract is a wrapper for Google's Tesseract Egnine, download Tesseract-OCR for windows: 
https://github.com/UB-Mannheim/tesseract/wiki
after download the Tesseract, locate the path as:
pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract'

2. Wand package is required, wand is a package binding with ImageMagick, install ImageMagick on Windows: https://legacy.imagemagick.org/script/download.php#windows
Wand also requires Ghostscript to scanning pdf file. To install Ghostscript, simply follow the link:
https://www.ghostscript.com/download.html

