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
[Webhook Trigger]
↓
[OpenAI - Summarize Manuscript]
↓
[OpenAI - Score & Recommendation]
↓
[Email Compose]
↓
[Email Send]



---

## 📁 Repository Files

| File | Description |
|------|-------------|
| `workflow.json` | Exported n8n workflow file |
| `screenshots/workflow.png` | Visual workflow layout |
| `screenshots/sample-email.png` | Example generated email |

---

## 🚀 Key Benefits

| Benefit | Result |
|---------|--------|
| Time saved per manuscript | **~30 minutes** |
| Manual dependency | **Reduced by 80%** |
| Consistency | **AI ensures objective scoring** |

---

## 📬 Sample Output (Email)


New High-Potential Manuscript for Review

Title: Python Chatbot: A Beginner's Guide
Publishability Score: 7 / 10
Recommendation: Accept

AI Summary:
The manuscript explains how to build a rule-based chatbot using Python...



---

## 🛠 How to Use

1. Import `workflow.json` into **n8n**
2. Configure **OpenAI API Key**
3. Add your **editorial team email**
4. Start the webhook → Submit manuscript → Done ✅

---

## 📌 Future Improvements

- Add **Genre Classification**
- Route **different reviewers per topic**
- Integrate **Plagiarism Check API**

