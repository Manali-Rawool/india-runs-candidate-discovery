# Intelligent Candidate Discovery

## Problem Statement
Match job descriptions with the most relevant candidates using Machine Learning.

## Dataset
Provided by India Runs - contains candidate profiles with skills, experience, education.

## Approach
1. **Text Preprocessing**: Clean job description and candidate resumes
2. **TF-IDF Vectorization**: Convert text to numerical vectors  
3. **Cosine Similarity**: Calculate similarity score between job and candidates
4. **Ranking**: Return top 10 matching candidates

## Tech Stack
Python, Pandas, Scikit-learn, TF-IDF, Cosine Similarity

## Results
Baseline model implemented. Future work: Use Sentence-BERT for better semantic matching.

## Author
Manali Rawool
