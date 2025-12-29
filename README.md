📌 Project Overview

Recruitment processes often rely on rigid filters that produce binary accept/reject decisions, which can overlook potentially suitable candidates. This project aims to design and develop an intelligent decision-support system using fuzzy logic to automate the initial screening of resumes.

Instead of making hard decisions, the system generates a Candidate Fit Score (0–100) that reflects how well a candidate matches a given job profile, providing a more flexible, human-like evaluation.

🎯 Objectives

Automate the initial resume screening process

Reduce bias caused by rigid rule-based systems

Provide a nuanced evaluation instead of binary decisions

Assist recruiters with a decision-support tool rather than replacing human judgment

🛠️ Key Features

Fuzzy Logic-Based Evaluation

Multi-criteria Assessment

Relevant Work Experience

Skill Match Percentage

Education Level

Candidate Fit Score (0–100)

Human-like reasoning through fuzzy inference rules

Easily customizable job profiles and criteria weights

🧩 System Architecture

Input Layer

Years of relevant experience

Skill match percentage

Education level

Fuzzification

Converts crisp inputs into fuzzy sets (Low, Medium, High)

Fuzzy Rule Base

IF–THEN rules simulating recruiter reasoning

Inference Engine

Evaluates rules using fuzzy operators

Defuzzification

Converts fuzzy output into a numerical Candidate Fit Score

📊 Input Parameters
Parameter	Description
Experience	Relevant work experience (in years)
Skill Match	Percentage match with required skills
Education Level	Academic qualification level
📈 Output

Candidate Fit Score (0–100)

0–39: Poor Fit

40–69: Moderate Fit

70–100: Strong Fit

This score helps recruiters quickly shortlist candidates while still allowing human judgment.

🧪 Technologies Used

Python

Fuzzy Logic (e.g., scikit-fuzzy)

NumPy

Matplotlib (for visualization)

Jupyter Notebook (optional for experimentation)

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/Thirukkumar2005/Screening-process-of-resumes-


Install dependencies:

pip install -r requirements.txt


Run the main script:

python main.py

📌 Example Use Case

A recruiter inputs:

Experience: 4 years

Skill Match: 75%

Education Level: Bachelor’s Degree

The system processes these inputs and outputs:

Candidate Fit Score: 78 → Strong Fit
