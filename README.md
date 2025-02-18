# **AI-Powered Email Automation for Job Applications**

## **Overview**
This project automates job application email management using AI-powered analysis and Gmail API integration. It streamlines interactions with recruiters by analyzing incoming emails, sending automated responses with resumes, and organizing messages into designated folders.

## **Features**

### ✅ Automated Email Processing
- Reads and categorizes recruiter emails using the Gmail API.
- Extracts relevant details and determines the appropriate action using AI.

### 📩 AI-Powered Resume Replies
- Generates personalized recruiter responses with an attached resume.
- Supports multiple LLMs (OpenAI, Anthropic, Google) for enhanced analysis and response quality.

### 🗂 Smart Email Organization
- Moves processed emails into categorized folders for better inbox management.
- Ensures easy access to recruiter communications.

### 🔍 Multi-Model Support & Performance Tracking
- Three AI-powered **Analyze Scripts** allow switching between OpenAI, Anthropic, and Google LLMs.
- An additional **LangSmith-integrated script** enables tracing and performance monitoring of AI responses.

### 🤖 Task Automation with CrewAI
- The `crew_ai.py` script orchestrates AI-driven workflows to manage multiple email-related tasks efficiently.

---

## **Setup & Installation**

### **1. Environment Configuration**
- Create an `.env` file in the root directory based on `.env_sample`.
- Set up Gmail API via Google Cloud and download `client_secret.json`.
- Upon first-time initialization, the `Gmail` class will generate a `gmail_token.json` for authentication persistence.

### **2. Install Dependencies**
Run the following command to install required packages:
```bash
pip install -r requirements.txt
```

---

## **Usage**

### **Running the Email Automation**
```bash
python analyze_script.py  # Choose from OpenAI, Anthropic, Google, or LangSmith versions
```

### **Running CrewAI Task Automation**
```bash
python crew_ai.py
```

---

## **Use Cases & Benefits**
- **Job Seekers**: Automates recruiter communication, reducing manual email handling.
- **Recruitment Professionals**: Organizes candidate emails efficiently for better tracking.
- **AI Enthusiasts & Developers**: Demonstrates practical AI-driven workflow automation.

---

## **Contributing**
Contributions are welcome! Feel free to submit a pull request or open an issue.

---
-

