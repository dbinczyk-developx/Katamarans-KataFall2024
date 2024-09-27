# Distilled Functional Requirements

During the elicitation process, we identified a set of functional and non-functional [requirements]() that are essential
for
the success of the AI-driven hiring platform. These requirements are distilled from the requirements prepare to
focus on the core functionalities and features that will provide the most value to the users. The distilled requirements
are categorized based on their primary functionality and are listed below:

| **Requirement ID** | Category        | **Requirement Name**           | **Description**                                                                                                                                                          |
|--------------------|-----------------|--------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| FR01               | Resume          | AI Resume Reconstruction       | The system must use AI to transform candidate resumes into S.M.A.R.T. goals (Specific, Measurable, Achievable, Relevant, Time-bound) and match them to job descriptions. |
| FR02               | Resume          | Bias-Free Candidate Evaluation | The system must anonymize resumes by removing all personal identifiers (race, gender, culture, etc.) to promote objective candidate evaluation.                          |
| FR03               | Resume          | Resume Improvement Suggestions | The AI must offer resume improvement suggestions to candidates based on their profile and job alignment.                                                                 |
| FR04               | Matching        | Similarity Scoring & Matching  | The platform must generate a similarity score between the candidate's qualifications and the job description to ensure proper alignment.                                 |
| FR05               | Matching        | Profile Unlocking              | Employers can only unlock and view the full candidate profile after making an objective decision based on the AI evaluation.                                             |
| FR06               | Reports         | Survey Feedback                | The platform must allow interviewers and job candidates to complete short (around 5-question) surveys on the interview process.                                          |
| FR07               | Reports         | Data Aggregation               | The backend must aggregate data on hiring decisions, capturing key data points such as candidate rejection, offers made, and demographic trends.                         |
| FR08               | Reports         | Reports                        | The platform must generate analytics reports on key performance indicators (KPIs) related to hiring practices and interview outcomes.                                    |
| FR09               | Reports         | Process observability          | The platform must provide DEI consultants with access to monitor interviews, provide ratings, and submit reports to executive management.                                |
| FR10               | AI              | AI engine improvement          | The AI resume anonymisation engine must be continuously improved based on feedback from DEI consultants and hiring managers.                                             |
| FR11               | Company details | Company details scraping       | The AI must scrape company details from the web to support filling its data during a registration.                                                                       |~~~~

# Non-Functional Requirements

| **Requirement ID** | **Category**         | **Requriement name** | **Description**                                                                                                                                     |
|--------------------|----------------------|----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| NFR01              | Non-Functional       |                      | The AI should offer a smooth user experience during a company registration and resume improving.                                                    |
| NFR02              | Non-Functional       |                      | The system must ensure seamless adoption by businesses by enabling integrations with major HR platforms (e.g., SAP, Workday, Paycom, Paylocity) to. |
| NFR03              | Non-Functional       |                      | DEI consultants should be able to monitor interviews, provide ratings, and submit reports to executive management to identify and reduce biases.    |
| NFR04              | Security and Privacy |                      | All personal identifiable information must be anonymized to prevent bias.                                                                           |
| NFR05              | Security and Privacy |                      | Candidate profiles and employer data must be securely stored, following relevant data protection regulations (e.g. CCPA).                           |
