# AI-Powered Resume Parser and Candidate Skills Analysis System

## Project Overview

The AI-Powered Resume Parser and Candidate Skills Analysis System is a Python-based application designed to automate the extraction and analysis of information from resumes.

The system processes resumes in PDF and DOCX formats, extracts candidate details, identifies technical skills, and organizes the extracted information for candidate search and analysis.

It also supports comparing candidate skills with job descriptions to help recruiters identify relevant skills.

## Objectives

* Automate resume information extraction.
* Identify candidate names, email addresses, and phone numbers.
* Extract technical skills and educational qualifications.
* Store extracted candidate information in a database.
* Compare candidate skills with job requirements.
* Search candidate records using technical skills.
* Export candidate information for further analysis.
* Visualize skills distribution across candidate records.

## Features

* PDF and DOCX resume processing.
* Candidate information extraction.
* Technical skills identification.
* Education information extraction.
* Job description and skills matching.
* Candidate search functionality.
* Database storage using SQLite.
* Candidate skills visualization.
* CSV export of extracted information.

## Technologies Used

* **Programming Language:** Python
* **Development Environment:** Google Colab
* **Natural Language Processing:** spaCy
* **PDF Processing:** PDFPlumber
* **DOCX Processing:** python-docx
* **Data Analysis:** Pandas
* **Database:** SQLite
* **Data Visualization:** Matplotlib

## Project Workflow

1. Upload a resume in PDF or DOCX format.
2. Extract readable text from the document.
3. Identify candidate information.
4. Extract technical skills and education details.
5. Store the extracted information in the database.
6. Compare candidate skills with a job description.
7. Search candidate records and analyze skills.
8. Export candidate information as a CSV file.

## How to Run the Project

### Option 1: Google Colab

1. Open the project notebook in this repository.
2. Download the notebook or open it in Google Colab.
3. Install the required Python libraries.
4. Execute the notebook cells in order.
5. Upload a sample PDF or DOCX resume when prompted.
6. Review the extracted candidate information and analysis results.

### Option 2: Run Locally

1. Install Python on your computer.
2. Download or clone this repository.
3. Install the required libraries.
4. Open the notebook in Jupyter Notebook or Google Colab.
5. Execute the cells in the correct order.

## Skills Matching

The system compares the technical skills identified in a resume with those found in a job description.

The skills-match percentage is calculated as:

**Skills Match Percentage = (Number of Matched Required Skills / Total Recognized Required Skills) × 100**

This score represents skills overlap only. It does not independently determine a candidate's overall suitability for a job.

## Limitations

* Resume formats differ, so extracted information may require manual verification.
* Name extraction may not be accurate for every resume.
* Skills are identified using a predefined skills dictionary.
* Scanned PDFs may require OCR processing.
* The skills-match score does not measure a candidate's complete qualifications or work performance.
* SQLite data stored in a temporary Google Colab runtime may be lost when the runtime resets.

## Privacy and Responsible Use

Resumes can contain personal and confidential information.

This project should be tested using fictional or authorized sample resumes. Real candidate information, private resumes, and databases containing personal information should not be published in the public repository.

Candidate information should be verified before it is used for recruitment decisions.

## Project Status

Completed prototype for resume parsing and candidate skills analysis. Features should be verified against the implementation and test results in the notebook.

## Author

**Name:** Your Name

## License

This project is intended for educational and internship purposes.
