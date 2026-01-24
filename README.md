# AI Resume Reviewer (n8n + Groq LLaMA)

An AI-powered resume review system that analyzes PDF resumes and provides
**structured, actionable feedback** including resume score, strengths,
weaknesses, improvement suggestions, and ATS friendliness.

Built using **n8n workflow automation**, **Groq LLaMA models**, and a
**custom HTML frontend**.

---

## 🚀 Features

- Upload resume in **PDF format**
- AI-based resume analysis
- Overall resume score
- Key strengths and major gaps
- Specific improvement suggestions
- ATS (Applicant Tracking System) friendliness score
- Clean, professional frontend UI
- Fully automated workflow using n8n

---

## 🛠 Tech Stack

- **n8n** – Workflow automation
- **Groq LLaMA** – Large Language Model inference
- **HTML / CSS / JavaScript** – Frontend UI
- **PDF Text Extraction** – Resume parsing
- **Webhook-based API** – Frontend ↔ Backend integration

---

## 🧠 How It Works

1. User uploads a resume PDF via the HTML frontend
2. The form submits data to an **n8n Webhook**
3. n8n extracts text from the PDF
4. Resume text is sent to **Groq LLaMA** for analysis
5. AI returns structured resume feedback
6. The frontend displays results in a professional format

---

## 📂 Project Structure

