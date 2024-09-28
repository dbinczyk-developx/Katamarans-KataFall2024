# Distilled Functional Requirements

During the elicitation requirements process based on [requirements](Requirements.md), we identified a set of functional
and non-functional that are essential
for the success of the AI-driven hiring platform. These requirements are distilled from the requirements prepare to
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

The non-functional requirements define the key attributes and performance standards that the system must meet to ensure
optimal operation, security, and user satisfaction. These requirements address how the system will perform under various
conditions and how it will interact with users, data, and external systems. In this chapter, we outline the critical
non-functional aspects such as user experience, security, performance, and system integration. These requirements are
essential for creating a robust, scalable, and secure platform that meets business needs and compliance standards.

| **Requirement ID** | **Category**         | **Requirement name**             | **Description**                                                                                                                                     |
|--------------------|----------------------|----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
| NFR01              | Non-Functional       | User Experience                  | The AI should offer a smooth user experience during a company registration and resume improving.                                                    |
| NFR02              | Non-Functional       | System Integration               | The system must ensure seamless adoption by businesses by enabling integrations with major HR platforms (e.g., SAP, Workday, Paycom, Paylocity) to. |
| NFR03              | Non-Functional       | Bias Monitoring                  | DEI consultants should be able to monitor interviews, provide ratings, and submit reports to executive management to identify and reduce biases.    |
| NFR04              | Security and Privacy | Data Anonymization               | All personal identifiable information must be anonymized to prevent bias.                                                                           |
| NFR05              | Security and Privacy | Secure Data Storage              | Candidate profiles and employer data must be securely stored, following relevant data protection regulations (e.g. CCPA).                           |
| NFR06              | Performance          | Scalability                      | The platform must scale to handle increasing numbers of users (employers, job seekers, admins) without performance degradation.                     |
| NFR07              | Usability            | Accessibility                    | The system must comply with accessibility standards (e.g., WCAG 2.1) to ensure usability for users with disabilities.                               |
| NFR08              | Performance          | Response Time                    | The platform must ensure that job searches, resume uploads, and profile updates have a maximum response time of 3 seconds.                          |
| NFR09              | Reliability          | Uptime                           | The system must maintain an uptime of 99.9% to ensure continuous availability for users during critical hiring periods.                             |
| NFR10              | Maintenance          | Maintainability                  | The system should be easy to maintain, allowing for quick updates, patching, and upgrades without significant downtime.                             |
| NFR11              | Security and Privacy | Data Encryption                  | All sensitive data (e.g., candidate profiles, employer information) must be encrypted both in transit and at rest.                                  |
| NFR12              | Security and Privacy | Audit Logging                    | The system must maintain detailed audit logs of all user activities (e.g., profile updates, hiring decisions) for accountability and traceability.  |
| NFR13              | Compatibility        | Browser and Device Compatibility | The platform must be compatible with all modern web browsers and provide a responsive design for mobile and tablet users.                           |