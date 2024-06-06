# Resume Classification and Label Extraction Web Application
This web application allows users to upload their resumes in PDF format and receive a classification of their resume into predefined job categories along with label extraction using a trained SpaCy model. The application uses Flask as the web framework and integrates machine learning models for text classification and named entity recognition.

## Features
### Resume Upload: 
Users can upload their resumes in PDF format.
### Resume Text Extraction: 
Extracts text from uploaded PDF resumes using pdfplumber.
### Text Cleaning: 
Cleans the extracted text by removing URLs, special characters, and extra spaces.
### Domain Classification: 
Classifies the cleaned text into job categories using a pre-trained TF-IDF vectorizer and a classifier model.
### Label Extraction: 
Extracts labeled entities from the resume text using a trained SpaCy model.
### Results Display: 
Displays the classified job category and extracted labels to the user.

