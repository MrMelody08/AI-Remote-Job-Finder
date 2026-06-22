
# 🚀 AI-Powered Remote Job Finder & Resume Matching System

An intelligent job discovery and AI-driven resume matching platform built using **n8n, Ollama, Qwen3, JavaScript, and Job APIs**. The system automatically fetches remote job opportunities, filters irrelevant roles, analyzes job descriptions using LLMs, and recommends the best opportunities for freshers and entry-level candidates.

---

## 📌 Overview

Finding relevant remote jobs as a fresher is time-consuming and inefficient. This project automates the entire process by combining workflow automation and AI-powered job analysis.

The system:

- Fetches remote jobs from public job APIs
- Filters language-restricted roles
- Eliminates senior and experience-heavy positions
- Identifies fresher-friendly opportunities
- Uses AI to evaluate job relevance
- Generates match scores and application recommendations
- Focuses on AI, Data Science, Data Analytics, Python, Automation, and Agentic AI roles

---

## ✨ Key Features

### 🔍 Intelligent Job Discovery
- Automatically collects remote job postings from online job platforms.
- Supports global remote opportunities.

### 🤖 AI-Powered Job Analysis
- Uses Ollama with Qwen3 LLM for job evaluation.
- Understands job descriptions and requirements.

### 🎯 Resume-to-Job Matching
- Compares candidate skills against job requirements.
- Generates job match scores.
- Provides application recommendations.

### 🚫 Smart Filtering
Automatically removes:
- French-language jobs
- German-language jobs
- Spanish-language jobs
- Japanese-language jobs
- Korean-language jobs
- Mandarin-language jobs
- Senior-level roles
- Lead roles
- Principal roles
- Manager positions
- Director positions
- Experience-heavy roles

### 🌍 Fresher-Focused Recommendations
Prioritizes:
- Remote opportunities
- Entry-level jobs
- Graduate programs
- Internships
- Trainee positions
- Associate roles
- AI/ML opportunities
- Data Analyst roles
- Python Developer roles
- Agentic AI roles

---

## 🛠️ Technology Stack

| Technology | Purpose |
|------------|----------|
| n8n | Workflow Automation |
| Ollama | Local LLM Runtime |
| Qwen3 | AI Job Analysis |
| JavaScript | Data Processing & Filtering |
| REST APIs | Job Data Collection |
| JSON | Workflow Configuration |

---

## ⚙️ Workflow Architecture

1. Fetch jobs from Job API
2. Process and clean job data
3. Filter non-relevant jobs
4. Remove language-restricted roles
5. Remove senior-level opportunities
6. Send jobs to AI Agent
7. Generate job suitability score
8. Recommend whether to apply
9. Store results for further processing

---

## 📸 Workflow Screenshots

### Complete Workflow

![Workflow Overview](https://raw.githubusercontent.com/MrMelody08/AI-Remote-Job-Finder/refs/heads/main/workflow%20overview.bmp)

### AI Agent Job Analysis

![AI Agent Filtering](https://raw.githubusercontent.com/MrMelody08/AI-Remote-Job-Finder/refs/heads/main/ai%20agent%20filtering.bmp)

---

## 📊 Example AI Output

```json
{
  "job_title": "AI Intern",
  "company_name": "Example Company",
  "match_score": 9,
  "apply": "yes",
  "reason": "Strong match for Python, SQL, Machine Learning and fresher profile."
}
```

---

## 🎯 Use Cases

- Remote Job Discovery
- Resume Matching
- AI-Powered Job Screening
- Career Opportunity Analysis
- Fresher Job Search Automation
- AI Career Assistant

---

## 🔮 Future Enhancements

- Telegram Notifications
- Email Alerts
- Multi-Source Job Aggregation
- Resume Upload & Parsing
- ATS Resume Scoring
- LinkedIn Integration
- Automated Application Tracking

---

## 👨‍💻 Author

**Pedatala Sri Ganesh**

B.Tech Computer Science Engineering (2025)

Skills:
- Python
- SQL
- Power BI
- Data Analytics
- Machine Learning
- Workflow Automation
- Generative AI
- Agentic AI

GitHub: https://github.com/MrMelody08

LinkedIn: https://www.linkedin.com/in/pedatala-sri-ganeshh-066046301

---

⭐ If you found this project useful, feel free to star the repository.
