# HireLens: A precise ATS (Application Tracking System) that analyzes and ranks resumes efficiently

## Overview

The Application Tracking System (ATS) is designed to automate the resume screening process by analyzing job descriptions and candidate resumes to provide a relevance score. By leveraging natural language processing (NLP) and machine learning techniques, the system enhances recruitment efficiency by reducing manual effort and ensuring an objective candidate evaluation process.

## Features

- **Resume Parsing:** Extracts text from PDF and DOCX resumes.
- **Text Preprocessing:** Tokenizes, removes stopwords, and lemmatizes text for better analysis.
- **Similarity Calculation:** Uses TF-IDF vectorization and cosine similarity to rank resumes.
- **Employer Mode:** Enables recruiters to input job descriptions for candidate evaluation.
- **Candidate Mode:** Allows applicants to submit resumes and receive relevance scores.
- **Jupyter Notebook-Based Interface:** Provides an interactive and structured environment for execution.

## Tech Stack

- **Python** – Core programming language used for processing and logic.
- **Jupyter Notebook** – Provides an interactive interface for executing the ATS system.
- **PyPDF2 & python-docx** – Extracts text from PDF and DOCX resume files.
- **NLTK (Natural Language Toolkit)** – Handles text tokenization, stopword removal, and lemmatization.
- **Scikit-learn** – Implements TF-IDF vectorization and cosine similarity for ranking resumes.
- **Pyfiglet & Termcolor** – Enhances CLI output with ASCII formatting and color styling.
- **OS Module** – Manages file handling operations.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/ATS.git
   cd ATS
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter Notebook:
   ```sh
   jupyter notebook ATS.ipynb
   ```
2. Run the notebook cells sequentially.
3. Choose `Employer Mode` to input job descriptions or `Candidate Mode` to evaluate resumes.
4. Follow the on-screen prompts to analyze resume relevance scores.

## Screenshots

### Employer Mode
![Image](https://github.com/user-attachments/assets/113ef61f-7cee-4ca4-b9d4-5f721d4ff916) <br/>

### Candidate Mode
![Image](https://github.com/user-attachments/assets/c56d2a0a-ea21-4b77-9a75-605753f46f1c) <br/>

## Contribution

Contributions are welcome. To contribute:

- Fork the repository.
- Create a new branch.
- Commit your changes.
- Submit a pull request.

## Acknowledgment

I would like to express my sincere gratitude to [Shruti Sahrawat](https://github.com/shrutisahrawat) for their valuable support and guidance throughout this project. Their insights and encouragement played a crucial role in shaping and refining this system.


