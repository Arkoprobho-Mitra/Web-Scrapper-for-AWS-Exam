# Web-Scrapper-for-AWS-Exam
a web scrapper using Beautiful Soup to scrap the web pages and provide a questionnaire in a word document.

from docx import Document

# Brief description for the README
"""
# Web Scraper for AWS Questionnaire

This project is a web scraper built using Python's Beautiful Soup library. It is designed to extract questions and related information from AWS-related questionnaires available online. The scraper efficiently parses HTML content to gather data, which can be stored locally or processed further for analysis.

## Features
- Extracts questions, answers, and metadata from AWS questionnaires.
- Handles various HTML structures with flexibility.
- Outputs data in a structured format for easy use.

## Requirements
- Python 3.x
- Beautiful Soup 4
- Requests library

## Usage
1. Install the required dependencies using `pip install -r requirements_libraries`("python-docx","beautifulsoup4").
2. Run the script and provide the URL of the AWS questionnaire as input.
3. View the extracted data in the output file (e.g., CSV, JSON).

## Disclaimer
Ensure compliance with website terms of service before scraping.
"""

# Create a Word document and add the description
doc = Document()
doc.add_heading("Web Scraper for AWS Questionnaire", level=1)
doc.add_paragraph(readme_description.strip())

# Save the document
file_path = "/mnt/data/Web_Scraper_ReadMe.docx"
doc.save(file_path)

file_path
