# Distilled Functional Requirements

During the elicitation process, we identified a set of functional and non-functional [requirements]() that are essential
for
the success of the AI-driven hiring platform. These requirements are distilled from the requirements prepare to
focus on the core functionalities and features that will provide the most value to the users. The distilled requirements
are categorized based on their primary functionality and are listed below:

| Category        | **Requirement ID** | **Requirement Name**           | **Description**                                                                                                                                                          |
|-----------------|--------------------|--------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Resume          | FR01               | AI Resume Reconstruction       | The system must use AI to transform candidate resumes into S.M.A.R.T. goals (Specific, Measurable, Achievable, Relevant, Time-bound) and match them to job descriptions. |
| Resume          | FR02               | Bias-Free Candidate Evaluation | The system must anonymize resumes by removing all personal identifiers (race, gender, culture, etc.) to promote objective candidate evaluation.                          |
| Resume          | FR03               | Resume Improvement Suggestions | The AI must offer resume improvement suggestions to candidates based on their profile and job alignment.                                                                 |
| Matching        | FR04               | Similarity Scoring & Matching  | The platform must generate a similarity score between the candidate's qualifications and the job description to ensure proper alignment.                                 |
| Matching        | FR05               | Profile Unlocking              | Employers can only unlock and view the full candidate profile after making an objective decision based on the AI evaluation.                                             |
| Reports         | FR06               | Survey Feedback                | The platform must allow interviewers and job candidates to complete short (around 5-question) surveys on the interview process.                                          |
| Reports         | FR07               | Data Aggregation               | The backend must aggregate data on hiring decisions, capturing key data points such as candidate rejection, offers made, and demographic trends.                         |
| Reports         | FR08               | Monthly Reports                | The platform must generate monthly analytics reports on key performance indicators (KPIs) related to hiring practices and interview outcomes.                            |
| Reports         | FR09               | Process observability          | The platform must provide DEI consultants with access to monitor interviews, provide ratings, and submit reports to executive management.                                |
| AI              | FR10               | AI engine improvement          | The AI resume anonymisation engine must be continuously improved based on feedback from DEI consultants and hiring managers.                                             |
| Job description | FR11               | Company details scraping       | The system must scrape company details from the web to auto-fill company data during registration.                                                                       |~~~~

| **Requirement ID** | **Category**         | **Description**                                                                                                                                                     |
|--------------------|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| NFR01              | Non-Functional       | The platform must provide an intuitive dashboard for employers to upload roles and manage candidates.                                                               |
| NFR02              | Non-Functional       | The AI should auto-fill company data during registration for a smooth user experience.                                                                              |
| NFR03              | Non-Functional       | The system must integrate with major HR platforms (e.g., SAP, Workday, Paycom, Paylocity) to ensure seamless adoption by businesses.                                |
| NFR04              | Non-Functional       | DEI consultants should be able to monitor interviews, provide ratings, and submit reports to executive management to identify and reduce biases.                    |
| NFR05              | Data and Analytics   | The system must capture and track the following data points: 1) Moving forward with a candidate 2) Unlocking full profiles 3) Surveys from candidates/interviewers. |
| NFR06              | Data and Analytics   | The system must capture demographic data related to rejected or hired candidates and provide detailed analysis of the data.                                         |
| NFR07              | Security and Privacy | All personal identifiable information must be anonymized to prevent bias.                                                                                           |
| NFR08              | Security and Privacy | Candidate profiles and employer data must be securely stored, following relevant data protection regulations (e.g., GDPR, CCPA).                                    |
