# FUTURE_ML_03
## Resume / Candidate Screening System using Machine Learning

### Machine Learning Internship Task 3  
**By Future Interns**

---

## 📌 Project Overview

Hiring teams receive hundreds of resumes for a single job role, making manual screening slow and inefficient.  
This project builds a **Machine Learning-based Resume Screening System** that automatically analyzes resumes, compares them with job requirements, and ranks candidates based on their suitability.

The system helps recruiters shortlist candidates faster, identify missing skills, and improve hiring efficiency.

---

## 🎯 Objective

The main objectives of this project are:

- Read and process resume text data
- Extract skills and important keywords
- Compare resumes with a given job description
- Rank candidates based on similarity scores
- Identify missing skills in each resume

---

## 📁 Dataset Used

The project uses a **Resume Dataset** containing resumes categorized into different job roles such as:

- Accountant
- Advocate
- Agriculture
- Arts
- Engineering
- HR
- IT
- Sales
- Management
- and more

Dataset contains:

- Resume text (Resume_str)
- Resume category (Category)
- Resume ID

---

## 🧠 Machine Learning / NLP Approach

The following Natural Language Processing techniques were used:

- Text preprocessing (cleaning, lowercasing, removing unwanted characters)
- TF-IDF Vectorization to convert resume text into numerical features
- Cosine Similarity to compare resumes with the job description
- Candidate ranking based on similarity scores
- Skill gap identification to find missing required skills

---

## 🛠 Tools & Technologies Used

- Python
- Pandas – Data processing
- NumPy – Numerical operations
- Scikit-learn – TF-IDF and similarity computation
- Matplotlib – Visualization
- Jupyter Notebook – Development environment

---

## ⚙️ Project Workflow

1. Load resume dataset
2. Clean and preprocess resume text
3. Define job description for the target role
4. Convert resumes and job description into TF-IDF vectors
5. Compute similarity scores between resumes and job description
6. Rank candidates based on scores
7. Identify missing skills for each candidate
8. Display top-ranked candidates

---

## 📊 Results

The system successfully:

- Ranked candidates according to job relevance
- Highlighted resumes with the highest matching scores
- Identified missing required skills for improvement

This demonstrates how Machine Learning can assist recruiters in faster and smarter hiring decisions.

---

## 🚀 Future Improvements

- Automatic skill extraction using spaCy
- Resume PDF parsing
- Web interface for recruiter use
- Multi-role job matching
- Real-time resume upload screening

---

## 📌 Conclusion

This project demonstrates a practical real-world application of **Natural Language Processing and Machine Learning** in recruitment automation.  
The system helps organizations reduce manual screening effort, improve hiring speed, and identify the most suitable candidates efficiently.
