Publishing teams often receive a high volume of manuscripts, and manually reading each submission to summarize, evaluate, and decide whether it’s suitable for review is time-consuming and inconsistent.

# 📚 Automated Manuscript Screening Pipeline (n8n + OpenAI)

## 🔍 Problem Statement
Publishing teams manually review every manuscript, which takes **30+ minutes per submission** and leads to **delayed decisions and inconsistent evaluations**.

## ✅ Solution
This project automates manuscript review using **n8n + OpenAI**.  
It summarises the document, scores it, recommends an action (Accept / Reject / Revise), and **emails the editorial team automatically**.

---

## 🧠 Tech Stack

| Tool / Service | Purpose |
|----------------|---------|
| n8n | No-code workflow builder |
| OpenAI GPT | AI-based summarization & scoring |
| Email Node (SMTP/Gmail) | Auto-notifications |

---

## 🔗 Workflow Structure

