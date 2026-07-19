# 📚 StudyPilot AI – Personalized Study Planner

> An AI-powered study planning system that automatically generates personalized study plans using Google Gemini AI, n8n automation, Google Forms, Google Sheets, and Gmail.

![SDG](https://img.shields.io/badge/SDG-4%20Quality%20Education-blue)
![Platform](https://img.shields.io/badge/Built%20With-n8n-orange)
![AI](https://img.shields.io/badge/AI-Google%20Gemini-green)
![Status](https://img.shields.io/badge/Project-Completed-success)

---

# 🌍 SDG Alignment

This project supports **United Nations Sustainable Development Goal (SDG) 4 – Quality Education** by helping students receive personalized AI-generated study plans based on their subjects, available study hours, and exam dates.

---

# 📖 Project Overview

StudyPilot AI is an intelligent study planning system that automates the process of creating personalized study schedules.

Students submit their information using a Google Form. The workflow automatically detects the submission, sends the data to Google Gemini AI through n8n, generates a customized study plan, stores it in Google Sheets, and emails the plan to the student.

The entire process is fully automated without any manual intervention.

---

# ❗ Problem Statement

Many students struggle to prepare effective study schedules before examinations. Creating a balanced study plan requires time and planning, and students often do not know how to divide their available time efficiently.

---

# 💡 Proposed Solution

StudyPilot AI automatically generates a personalized study plan using Artificial Intelligence.

The system:

- Collects student information
- Understands available study time
- Generates a customized day-by-day plan
- Stores the plan
- Delivers it instantly through email

---

# 🎯 Objectives

- Help students prepare efficiently
- Reduce manual planning effort
- Demonstrate AI-powered workflow automation
- Improve accessibility to personalized learning support

---

# ✨ Features

- 🤖 AI-generated study plans
- 📄 Google Forms integration
- 📊 Google Sheets database
- ⚙️ n8n workflow automation
- 📧 Automatic HTML email delivery
- ☁️ Cloud-based execution
- ⚡ Fully automated process

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| n8n | Workflow Automation |
| Google Gemini AI | AI Study Plan Generation |
| Google Forms | User Input |
| Google Sheets | Data Storage |
| Gmail | Email Delivery |
| Google Cloud APIs | Integration |

---

# 🔄 Workflow

Student fills Google Form

⬇️

Google Sheets Trigger

⬇️

Google Gemini AI

⬇️

Generate Personalized Study Plan

⬇️

Store in Google Sheets

⬇️

Send HTML Email to Student

---

# 🏗 System Architecture

```text
Google Form
      │
      ▼
Google Sheets Trigger
      │
      ▼
Google Gemini AI
      │
      ▼
Generate Study Plan
      │
      ▼
Append to Google Sheets
      │
      ▼
Send Email via Gmail
```

---

# 📂 Repository Structure

```
StudyPilot-AI
│
├── README.md
├── StudyPilotAI_Workflow.json
├── screenshots/
├── docs/
```

---

# 🚀 How It Works

1. Student submits the Google Form.
2. Google Sheets receives a new response.
3. n8n automatically detects the new row.
4. Google Gemini AI generates a personalized study plan.
5. The generated plan is stored in Google Sheets.
6. A professional HTML email is sent to the student.

---

# 📸 Screenshots

The following screenshots will be added:

- Google Form
- n8n Workflow
- Google Sheets Responses
- StudyPlan Database
- HTML Email Output

---

# 🔮 Future Enhancements

- Student login system
- PDF study plan generation
- Calendar integration
- WhatsApp notifications
- Mobile application
- Multi-language support
- Progress tracking dashboard

---

# 👥 Team Members

| Name | Role |
|------|------|
| Dhruv Singh | Project Developer |
| Bansil Savaliya | Project Developer |

---

# 📜 License

This project was developed as part of the **IBM SkillsBuild AI & Automation Internship** for learning and educational purposes.

---

## ⭐ Acknowledgements

- IBM SkillsBuild
- n8n
- Google Gemini AI
- Google Forms
- Google Sheets
- Gmail
