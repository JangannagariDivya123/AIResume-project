# AI Resume Screening & Candidate Ranking System

## Overview
This project is a **Streamlit** web application that helps recruiters automatically rank resumes based on their relevance to a given job description. It uses **TF-IDF Vectorization** and **Cosine Similarity** to evaluate how well each resume matches the job posting.

## Features
- **Upload multiple resumes** (PDF format)
- **Enter a job description**
- **Automatically rank resumes** based on similarity to the job description
- **Provide improvement suggestions** for each resume
- **Visualize ranking results** in a styled dataframe

## Technologies Used
- **Python**
- **Streamlit**
- **PyPDF2** (for extracting text from PDFs)
- **Scikit-learn** (for TF-IDF and cosine similarity calculations)
- **NumPy** & **Pandas** (for data manipulation)

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/JangannagariDivya123/AIResume-project
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the application:
   ```sh
   streamlit run app.py
   ```

## Usage
1. Open the **Streamlit web app** in your browser.
2. Upload one or more **PDF resumes**.
3. Enter the **job description** in the text area.
4. View **ranked resumes** based on match percentage.
5. Explore **improvement suggestions** to optimize resumes for better matching.
