-- **AI-Powered Email Automation for Job Applications**
- **Project Overview**
- This project automates job application email management using AI-powered analysis and Gmail API integration. By leveraging multiple large language models (LLMs) and Google Cloud's OAuth 2.0 authentication, the system streamlines interactions with recruiters by analyzing incoming emails, sending automated responses with resumes, and organizing messages into designated folders.
-This project simplifies job search email management by integrating AI-based decision-making with automated email handling. Whether responding to recruiters, organizing emails, or optimizing workflow tracking, the system enhances productivity and ensures seamless communication.

-**Key Features**
-1. Automated Email Processing
Uses the Gmail API to read and categorize incoming recruiter emails.
Extracts relevant details using AI and determines appropriate actions.
2. AI-Powered Resume Replies
Automatically generates and sends recruiter responses with the applicant’s resume attached.
Uses different LLMs (OpenAI, Anthropic, and Google) to enhance analysis and improve email response quality.
3. Smart Email Organization
Moves processed emails into categorized folders for better inbox management.
Ensures that recruiter communications are easily accessible.
4. Multi-Model Support & Performance Tracking
Three separate AI-driven Analyze Scripts allow switching between OpenAI, Anthropic, and Google LLMs.
A specialized LangSmith-integrated script enables tracing and performance monitoring of AI responses.
5. Task Automation with CrewAI
The crew_ai.py script orchestrates AI-driven workflows to manage multiple email-related tasks efficiently.
Technical Setup
1. Environment Configuration
.env file setup for secure environment variable management, based on .env_sample.
Google Cloud OAuth 2.0 authentication with a downloaded client_secret.json.
Upon first-time initialization, the Gmail class generates a gmail_token.json file for authentication persistence.
2. Dependency Management
Install required dependencies using:
bash
Copy
Edit
pip install -r requirements.txt
Use Cases & Benefits
Job Seekers: Automates recruiter communication, reducing manual email handling.
Recruitment Professionals: Organizes candidate emails efficiently for better tracking.
AI Enthusiasts & Developers: Demonstrates practical AI-driven workflow automation.

