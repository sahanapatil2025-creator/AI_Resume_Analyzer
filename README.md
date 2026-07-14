
ResumeIQ_Link: https://ai---resume--analyzer-rsew2db9aocexanwqfd3sw.streamlit.app/





# AI_Resume_Analyzer
An intelligent AI-powered Resume Analyzer that helps job seekers evaluate and improve their resumes by comparing them against a specific job description. The tool simulates how Applicant Tracking Systems (ATS) and recruiters assess resumes, providing actionable insights to increase the chances of getting shortlisted.

🚀 Built completely in a single Python file for simplicity and easy deployment.

🔍 What Does This Project Do?

📄 Resume Text Extraction

Users upload their resumes in PDF format, and the system automatically extracts the text content for analysis.

💼 Job Description Input

The user provides the job description for the position they are targeting. This serves as the benchmark against which the resume is evaluated.

🎯 ATS Similarity Score

Using Sentence Transformers (BERT-based embeddings), the tool calculates a similarity score between the resume and job description. This score reflects how closely the resume matches the role's requirements, keywords, and context typically scanned by ATS software.

🤖 AI-Powered Resume Evaluation

Powered by Groq's Llama-based Large Language Model, the application generates a detailed evaluation report covering:

Skills alignment
Experience relevance
Educational qualifications
Strengths and weaknesses
Missing requirements
Overall suitability for the role
Each category is scored out of 5 and presented using clear indicators:

✅ Strong Match
⚠️ Needs Improvement
❌ Missing or Weak Areas
💡 Actionable Feedback

Beyond scoring, the AI provides personalized recommendations to help candidates improve their resumes and better align them with job requirements.

📥 Downloadable Report

Users can download the complete analysis report for future reference and resume optimization.

Why Use This Tool?

Optimize resumes for ATS screening systems.
Identify missing skills and keywords.
Receive professional AI-driven feedback instantly.
Improve resume-job alignment before applying.
Increase chances of securing interviews.
Save time compared to manual resume reviews.
✨ Key Features

PDF Resume Upload & Text Extraction
Job Description Analysis
ATS Similarity Matching
AI-Based Resume Review
Detailed Category-wise Scoring
Personalized Improvement Suggestions
Downloadable Analysis Reports
Single-File Python Implementation
🛠️ Tech Stack

Python
Streamlit
Sentence Transformers
Groq API
PDF Processing Libraries
🚀 Workflow

Upload your resume (PDF).
Paste the target job description.
Run the analysis.
View ATS similarity score.
Receive AI-generated evaluation and recommendations.
Download the final report.
📊 Example Analysis

ATS Similarity Score

text 87.5%

Evaluation Summary

Category	Score
Skills Match	4/5
Experience Relevance	5/5
Education	4/5
Overall Fit	4/5
AI Recommendations

Add more role-specific keywords.
Quantify achievements with measurable results.
Highlight relevant technical skills.
Include additional certifications if applicable.
📂 Project Structure

text AI-Resume-Analyzer/ │ ├── main.py ├── README.md └── requirements.txt

Built to help job seekers create stronger, ATS-friendly resumes and improve their chances of landing interviews 🚀
