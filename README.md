# 📋 Zoho Resume Parser (Python)

This project automates the process of screening resumes received via email by extracting key candidate details and organizing them into a structured sheet. It acts as simple ATS (Applicant Tracking System) alternative for small teams or HR departments without a paid tool.
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

