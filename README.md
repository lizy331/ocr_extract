# ocr_extract
ocr program to extract information form pdf, png, jpg, tiff files.

# Geting Started:
Tesseract is required, download Tesseract for windows: 
https://sourceforge.net/projects/tesseract-ocr-alt/files/
after download the Tesseract, locate the path as:
pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract'

wand package is required, wand is a package binding with ImageMagick, install ImageMagick on Windows: https://legacy.imagemagick.org/script/download.php#windows
wand also requires Ghostscript to scanning pdf file.
