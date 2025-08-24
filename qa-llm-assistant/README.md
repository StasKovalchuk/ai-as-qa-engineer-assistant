# QA Assistant (LLM) — Quick Start

This project generates:
- ✅ Structured **Confluence documentation**
- ✅ Markdown **test cases** for **Testomat.io**  
based on **Jira tickets** using **OpenAI GPT-4**.

---

## ⚙️ Requirements

- OpenAI API key  
- Atlassian Cloud (email + API token)  
- Testomat.io API token  
- Google Drive (for `.env`)  
- Google Colab

---

## 📄 .env file (create in your Google Drive)

**Path:** `/content/drive/MyDrive/Colab_Notebooks/projectQaAssistant/.env`

# OpenAI
OPENAI_API_KEY=sk-...

# Atlassian
ATLASSIAN_EMAIL=your@email.com
ATLASSIAN_API_KEY=your_atlassian_token
JIRA_BASE_URL=https://your-domain.atlassian.net
CONFLUENCE_BASE_URL=https://your-domain.atlassian.net/wiki

# Testomat.io
TESTOMAT_API_KEY=your_testomat_token
