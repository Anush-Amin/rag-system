# Step 1: Document Ingestion
1) Files: pdf_loader.py, docx_loader.py, html_loader.py
2) Use pdfplumber or PyMuPDF for PDFs.
3) Use python-docx for Word files.
4) Use BeautifulSoup for HTML.
5) Return raw text + metadata (doc name, page number, section).