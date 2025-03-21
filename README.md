# Smart India Hackathon Workshop
# Date:21/3/2025
## Register Number:212224240028
## Name:CHIIRADEEP R
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
The proposed solution is a web-based simulation software that replicates a real-life board room interview experience for both interviewers and candidates. The software will use AI-powered question suggestion and relevance grading to ensure that questions and responses are aligned with the candidate’s expertise and the job requirements. It will provide a quantifiable scoring system to evaluate candidates objectively and assist in decision-making.


## Proposed Solution / Architecture Diagram
High-Level Architecture

1. The architecture consists of the following components:

2. Frontend: User interface for candidates and interviewers.

3. Backend: Handles business logic, data processing, and integration with AI/ML models.

4. Database: Stores user data, questions, responses, and scores.

5. AI/ML Module: Powers question suggestion and relevance grading.

6. Video Conferencing Module: Enables real-time interaction between candidates and interviewers.

7. Security Layer: Ensures data encryption and secure communication.
   
<img width="424" alt="web-application-architecture-and-diagram" src="https://github.com/user-attachments/assets/5aabc813-1fef-447d-bc17-150c9deb6231" />

## Use Cases
Use Case 1: Candidate Registration and Profile Creation
Actor: Candidate

Description: Candidates register on the platform, upload their resumes, and create profiles.

Steps:

Candidate visits the platform and signs up.

Uploads resume and fills in personal and professional details.

System analyzes the resume and suggests relevant job positions.

Use Case 2: Interview Scheduling
Actor: Admin

Description: Admin schedules interviews based on candidate applications and interviewer availability.

Steps:

Admin logs in and views candidate applications.

Assigns interviewers and schedules interviews.

Notifies candidates and interviewers via email.

Use Case 3: Conducting the Interview
Actor: Interviewer and Candidate

Description: Interviewer conducts the interview using the platform, asks questions, and evaluates responses.

Steps:

Interviewer and candidate join the virtual board room.

System suggests relevant questions based on the candidate’s profile.

Interviewer asks questions and evaluates responses in real-time.

Use Case 4: Scoring and Feedback
Actor: Interviewer

Description: Interviewer provides scores and feedback for the candidate.

Steps:

Interviewer evaluates responses and assigns scores.

System generates an overall score based on relevance and depth of responses.

Interviewer provides constructive feedback to the candidate.

Use Case 5: Report Generation
Actor: Admin

Description: System generates a detailed report for each candidate.

Steps:

Admin views the candidate’s performance metrics.

System generates a report with quantifiable scores and feedback.

Admin uses the report for final decision-making.
![gm8kr28v1](https://github.com/user-attachments/assets/039588ed-700e-468e-bfe3-70aa818888cd)

## Technology Stack
Frontend:
Framework: React.js or Angular

Languages: HTML, CSS, JavaScript

Libraries: Axios for API calls, Material-UI for design

Backend:
Framework: Node.js with Express or Django

Languages: JavaScript (Node.js) or Python (Django)

APIs: RESTful APIs for communication between frontend and backend

Database:
Primary Database: MongoDB (NoSQL) or PostgreSQL (SQL)

Use Case: MongoDB for flexible data storage, PostgreSQL for structured data

AI/ML Module:
Framework: TensorFlow or PyTorch

NLP Libraries: SpaCy, NLTK, or Hugging Face Transformers

Use Case: Question suggestion and relevance grading

Video Conferencing:
Technology: WebRTC or integration with Zoom/Google Meet API

Use Case: Real-time interaction between candidates and interviewers

Security:
Encryption: SSL/TLS for secure communication

Authentication: OAuth2 for user authentication

Authorization: Role-based access control (RBAC)

Deployment:
Cloud Platform: AWS, Azure, or Google Cloud

Containerization: Docker for easy deployment

CI/CD: Jenkins or GitHub Actions for continuous integration and deployment


## Dependencies:
![image](https://github.com/user-attachments/assets/562c416b-55b2-42a3-ac70-f7cd30b71930)

![image](https://github.com/user-attachments/assets/d59ee083-5909-4355-b250-3c62b4aeacae)



