# 📄 Resume Screening & Ranking System using NLP
Project Name

## Resume Screening & Ranking System

## Objective

This project builds a decision-support ML system to help HR professionals screen resumes efficiently.
It cleans resumes, extracts key skills, compares them with a job description, ranks candidates, and identifies missing skills.

## Features

Resume text cleaning & preprocessing

Skill extraction using TF-IDF (NLP technique)

Job description parsing

Resume-to-role similarity scoring (Cosine Similarity)

Candidate ranking based on role fit

Skill gap identification

Visualization of top candidates

## Dataset

Input: resume.csv (contains unstructured resumes)

Output: Resume_Ranking_Sample.csv (sample of top 50 ranked candidates)

Full dataset is large. Sample file is provided to showcase project output.

## How to Run

Open the Jupyter Notebook: Resume_Screening_Project.ipynb

Run all cells in order.

The final ranked candidates are saved in Resume_Ranking_Sample.csv.

## Future Improvements

Weight important skills for better scoring

Use advanced NLP models like BERT for more accurate skill extraction

Build a web interface for real-time resume screening

Handle multiple job descriptions at once
