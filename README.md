# Scrapping-From-PDF

This project automates the extraction of structured information from **PDF documents** and **web pages** using Python—designed to efficiently process hundreds to thousands of files or URLs at scale.

Originally developed to collect **ESG (Environmental, Social, Governance) metrics** and **financial report data** from corporate disclosures (e.g., annual reports, sustainability reports, investor presentations), the pipeline handles:
- Text extraction from scanned and native PDFs (via PyPDF2, pdfplumber, and OCR with Tesseract when needed)  
- Web scraping of publicly available reports and data tables (using BeautifulSoup and Selenium for dynamic content)  
- Targeted parsing of key sections (e.g., emissions data, governance policies, financial figures) using rule-based and NLP-assisted methods  
- Output in structured formats (CSV, JSON, or database-ready tables) for downstream analysis  

The modular design allows easy adaptation to new document layouts or sources. Aimed at reducing manual effort in large-scale data collection, this tool supports reproducible, transparent, and scalable ESG and financial intelligence gathering.
