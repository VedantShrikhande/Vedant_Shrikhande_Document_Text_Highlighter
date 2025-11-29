Document Text Highlighter

Python tool to search for text in PDFs, images (PNG/JPG), Word DOCX, Excel XLSX files and highlight matches with red unfilled bounding boxes in a new output file.

Features
1.  Case-insensitive search
2. Red vector rectangles
3. No original file modification

Step 1: Installation of Dependencies:
!pip install PyMuPDF
!pip install pytesseract
!sudo apt install tesseract-ocr
!pip install python-docx

Step 2: Run the Code, Interaction and File Upload
The program will prompt you for interaction in the following sequence:

File Upload: A file selection widget will pop up. Upload your target document (PDF, DOCX, XLSX, or PNG/JPG). 
Text Input: You will be prompted to enter the specific text string you want to search for and highlight.
Processing: The script will analyze the file, locate the text, and create the output file.
Auto Download: Upon successful processing, the Colab environment will automatically initiate a download of the highlighted file to your local machine.
