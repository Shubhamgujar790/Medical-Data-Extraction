# Medical-Data-Extraction



# Automated Medical Data Extraction System

## Overview

Health insurance companies often face challenges in processing claims efficiently due to the manual extraction of information from patient details and prescriptions. This project aims to automate the data extraction process using Python and various technologies to enhance accuracy, reduce processing time, and minimize errors associated with manual entry.

## Problem Statement

In the current scenario, health insurance companies rely on manual data entry for extracting information from scanned patient details and prescriptions. This process is not only time-consuming but also prone to errors. Outsourcing this task, especially during peak times such as the pandemic, becomes impractical. The need for a 24-hour data submission deadline adds additional pressure.

## Solution Approach

Our solution involves the development of a Python-based program that automates the extraction of data from medical images. The system utilizes technologies such as pytesseract for OCR, Pdf2image for PDF support, OpenCV for image processing, and regular expressions for refining extracted data. The combination of automation and human validation ensures both speed and accuracy in the data extraction process.

## Key Features

1. **Automation:** Extracts patient details and prescription information automatically from medical images.
  
2. **Error Reduction:** Human validation cross-checks and verifies the accuracy of the extracted data.
  
3. **Efficiency:** Meets the 24-hour data submission requirement through a faster and automated extraction process.

## Technology Stack

- **Python:** The core programming language.
  
- **Object-Oriented Programming (OOP):** Ensures modular and scalable code design.
  
- **Pdf2image:** Supports the extraction of information from PDF files.
  
- **OpenCV:** Utilized for image processing to enhance data extraction accuracy.
  
- **pytesseract:** Leverages Google's OCR technology for text extraction from images.
  
- **Regular Expression (Regex):** Facilitates data processing and refining for precise output.
  
- **pytest:** Used for automated testing to ensure code reliability.
  
- **Postman:** Employed for API testing and validation.
  
- **FastAPI:** Enables the development of a robust and efficient API for seamless integration.

**Benefits:**
- **Time Savings:** Automation significantly reduces the time required for data extraction, enabling faster claims processing.
  
- **Cost Efficiency:** The automated process minimizes the need for a large manual workforce, leading to cost savings for insurance companies.
  
- **Error Mitigation:** Human validation ensures accuracy, reducing the likelihood of errors in extracted data.

By implementing this automated medical data extraction system, we aim to streamline the claims processing workflow, making it more efficient, accurate, and cost-effective for health insurance companies.

## How to Use



1. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the Program:**
   ```bash
   python main.py
   ```

4. **run uvicorn server in command prompt:**
   ```bash
   uvicorn main:app  --reload
   ```

3. **Access the API:**
   - The API can be accessed at `http://localhost:8000`

## Testing

Automated tests have been implemented using `pytest`. Run the tests using the following command:

```bash
pytest tests/
```

