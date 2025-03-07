# Resume-Screening
# AI Resume Screening & Candidate Ranking System

## Overview

This project is an AI-powered resume screening and candidate ranking system built using Streamlit, Python, and various machine learning libraries. The system allows recruiters to upload multiple resumes in PDF format and input a job description. It then ranks the resumes based on their similarity to the job description using **TF-IDF Vectorization** and **Cosine Similarity**.

The system provides a user-friendly interface to visualize the ranking of resumes, including a table of scores and a bar chart. The best-matching resume is highlighted for quick identification.

## Features

- **PDF Resume Parsing**: Extracts text from uploaded PDF resumes.
- **Text Preprocessing**: Cleans and preprocesses the text from resumes and job descriptions.
- **TF-IDF Vectorization**: Converts text into numerical vectors for comparison.
- **Cosine Similarity**: Calculates the similarity between the job description and each resume.
- **Interactive Dashboard**: Built using Streamlit, providing a clean and intuitive interface.
- **Visualization**: Displays resume scores in a table and a bar chart using Plotly.
- **Best Resume Highlighting**: Automatically identifies and highlights the best-matching resume.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/ai-resume-screening.git
   cd ai-resume-screening
   ```

2. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

   Alternatively, you can install the dependencies manually:
   ```bash
   pip install streamlit PyPDF2 plotly scikit-learn
   ```

3. **Run the Streamlit app**:
   ```bash
   streamlit run app.py
   ```

4. **Access the app**:
   - Open your browser and navigate to `http://localhost:8501`.
   - Upload resumes and input a job description to see the ranking results.

## Usage

1. **Input Job Description**:
   - On the left sidebar, enter the job description in the provided text area.

2. **Upload Resumes**:
   - Use the file uploader to upload multiple resumes in PDF format.

3. **View Results**:
   - The app will display a table with the ranking of resumes based on their similarity to the job description.
   - A bar chart will visualize the match scores.
   - The best-matching resume will be highlighted at the bottom.

## Technologies Used

- **Streamlit**: For building the interactive web application.
- **PyPDF2**: For extracting text from PDF resumes.
- **Scikit-learn**: For TF-IDF Vectorization and Cosine Similarity calculations.
- **Plotly**: For creating interactive visualizations.
- **Pandas**: For data manipulation and displaying results in a tab
