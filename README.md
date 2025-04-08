# AI-Driven-Exam-Assessment-System
AI-Driven Exam Evaluation -   Expanding Adaptability and Transparency. 
Automated Answer Evaluation 
Reduces manual effort in grading subjective answers
Extract student responses from PDFs
Compare with correct answers
Supports both one-word and long-form answers with different evaluation methods  
AI models
SentenceTransformer for semantic similarity
TextBlob for spelling correction.  
Key point analysis 
Provide relevant information in answers
The goal
Accurate scoring
Detailed feedback to students

# Problem Statement
Develop a  multi-type AI driven Exam Evaluation system that evaluates diverse types of answers and provide transparent feedback to students

# Objectives
1.Collect the dataset
2.Study and select appropriate AI models and tools
3.Design the grading system for different answer formats
4.Develop the system 
5.Test and Validate the system

# Tools used
pandas (CSV processing)
pdfplumber (PDF extraction)
sentence-transformers
 sklearn
TextBlob
Regex (re)


# Methadology
Extract Data
Read answers from a PDF (pdfplumber)
Preprocess
Clean text
Spelling correction (TextBlob)
Extract questions and answers
Evaluate
One-word answers → Exact match
Long answers
Semantic similarity using SentenceTransformer
Key point matching with regex
Score & Feedback
Adjust scores based on similarity and missing key points
Generate feedback


# Software Requirements
Frontend
HTML, CSS, Javascript
Backend
Python , Python frameworks and libraries
Database
Firebase, SQLAlchemy
Tools


# Hardware Requirements
RAM: 8 GB(minimum)
HDD 
Scanner/PDF converter

# System Architecture
![image](https://github.com/user-attachments/assets/60744c30-9017-445a-bb95-9dd2aca9e6e5)

# Data Flow Diagram
![image](https://github.com/user-attachments/assets/34096aa8-726a-4ced-8eef-69d7de8deb28)
![image](https://github.com/user-attachments/assets/868edaac-0884-42e1-be31-a5febe0da8e3)

# Use Case Diagram
![image](https://github.com/user-attachments/assets/cb4bb42f-4c82-4483-a5fc-bc84788de208)

# Algorithms
PDF Extraction & Cleaning
pdfplumber, regex
Spelling Correction
TextBlob
Text Segmentation
Regex for separating Q&A
Semantic Similarity
SentenceTransformer (all-MiniLM-L6-v2) 
Cosine similarity (sklearn)
Key Point Matching
Regex-based keyword extraction and scoring
Final Score
Weighted average of semantic similarity
Key point presence

# Result
![image](https://github.com/user-attachments/assets/aefe8962-0cf0-4e92-9061-cd889e520cae)

# Conclusion
Exam assessment system using Transformer
Evaluates one word and long answers
Provides accurate, fair and transparent scoring
Reduces manual grading effort
Provides detailed feedback to students 

# Future Enhancement
Support for Handwritten Answers 
Integrate OCR (e.g., Tesseract) to process scanned answer sheets
Advanced NLP for Better Scoring 
Use BERT/RoBERTa for deeper semantic understanding
Multi-Language Support
Extend AI to evaluate answers in different languages
















