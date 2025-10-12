# 📋 Zoho Resume Parser (Python)

This script automatically connects to a Zoho Mail inbox, downloads resumes,
extracts candidate details, and builds an Excel file for HR shortlisting.

## 🚀 Features
- Connects to Zoho Mail via IMAP
- Downloads PDF/DOCX resumes
- Extracts Name, Email, Phone, Location, Position
- Finds skills automatically
- Exports results to `candidates.xlsx`

## ▶️ Run
```bash
pip install -r requirements.txt
python resume_parser.py
