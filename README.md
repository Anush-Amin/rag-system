# Summary: 
Develop a RAG (Retrieval-Augmented Generation) system that helps users find information and generate responses from large technical documentation repositories. 

# Problem Statement: 
Technical documentation is often extensive and difficult to navigate, leading to inefficient information retrieval. Your task is to build a RAG system that indexes technical documents, retrieves relevant sections based on user queries, and generates accurate, contextual responses. The system should handle various document formats, maintain source attribution, and provide up-to-date information from evolving documentation.

# Step 1: Document Ingestion
1) Files: pdf_loader.py, docx_loader.py, html_loader.py
2) Use pdfplumber or PyMuPDF for PDFs.
3) Use python-docx for Word files.
4) Use BeautifulSoup for HTML.
5) Return raw text + metadata (doc name, page number, section).