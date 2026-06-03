# Resume Screening & Candidate Ranking System
## Project Overview

The Resume Screening & Candidate Ranking System is a Machine Learning and Natural Language Processing (NLP) project designed to automate the initial recruitment process. The system analyzes resumes, extracts relevant skills, compares them with a given job description, ranks candidates based on their suitability, and identifies missing skills.

This project demonstrates how AI-powered recruitment tools can assist HR teams in reducing manual effort and improving candidate shortlisting efficiency.

---

## Problem Statement

Recruiters often receive hundreds of resumes for a single job opening. Manually reviewing each resume is time-consuming and prone to inconsistencies.

This project addresses that challenge by:

* Automatically processing resume text
* Extracting technical skills
* Comparing resumes against job requirements
* Ranking candidates based on relevance
* Highlighting skill gaps
* Generating recruiter-friendly recommendations

---

## Features

### Resume Processing

* Resume text cleaning and preprocessing
* Stopword removal and normalization
* NLP-based text handling

### Skill Extraction

* Identification of technical skills from resumes
* Matching extracted skills with job requirements

### Candidate Ranking

* TF-IDF Vectorization
* Cosine Similarity Scoring
* Automated ranking of candidates

### Skill Gap Analysis

* Detection of missing skills
* Candidate-specific skill gap reports

### Recruiter Recommendations

* Strong Match
* Consider
* Reject

### Data Visualization

* Candidate ranking charts
* Match score visualization

---

## Technologies Used

| Technology   | Purpose                                   |
| ------------ | ----------------------------------------- |
| Python       | Core Development                          |
| Pandas       | Data Processing                           |
| NLTK         | Text Preprocessing                        |
| Scikit-learn | Machine Learning & Similarity Calculation |
| Matplotlib   | Data Visualization                        |
| Google Colab | Development Environment                   |

---

## Project Workflow

```text
Resume Dataset
       ↓
Text Cleaning
       ↓
Skill Extraction
       ↓
Job Description Processing
       ↓
TF-IDF Vectorization
       ↓
Cosine Similarity
       ↓
Candidate Scoring
       ↓
Candidate Ranking
       ↓
Missing Skill Analysis
       ↓
Recruiter Recommendation
```

---

## Results

The system successfully:

* Ranked candidates based on job relevance
* Extracted skills from resume text
* Identified missing skills
* Generated recruiter recommendations
* Produced visual reports for candidate evaluation

---

## Sample Output

* Candidate Match Score
* Recommendation Status
* Extracted Skills
* Missing Skills
* Ranked Candidate List

Example:

| Candidate ID | Score | Recommendation |
| ------------ | ----- | -------------- |
| 62994611     | 15.06 | Strong Match   |
| 18448085     | 14.21 | Strong Match   |
| 12011623     | 13.63 | Strong Match   |

---

## Future Enhancements

* PDF Resume Parsing
* Streamlit Web Application
* Advanced Skill Weighting
* Deep Learning-based Resume Matching
* Recruiter Dashboard
* Real-Time Resume Screening

---

## Internship Task

**Future Interns – Machine Learning Task 3 (2026)**

Project: Resume / Candidate Screening System

---

## Author

**Vijitha Raj**

Machine Learning Intern – Future Interns

