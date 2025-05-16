# Deep-Learning--project
AI job resume matcher using BERT Embedding

## Overview
This project aims to automate the process of matching job descriptions with candidate resumes using advanced NLP techniques. It leverages BERT embeddings to understand the semantic meaning of both resumes and job descriptions, and ranks resumes based on their similarity to the job role.

## Key Features
- Extracts and preprocesses text from resumes and job descriptions.
- Generates contextual embeddings using pre-trained BERT models.
- Uses cosine similarity to calculate match scores between resumes and job roles.
- Returns top-N most relevant resumes for any given job posting.

## Technologies Used
- Python
- Transformers (BERT)
- Scikit-learn
- Pandas, NumPy

## Use Case
Ideal for HR teams, job portals, or ATS systems to quickly shortlist candidates based on skill relevance and job fit.
