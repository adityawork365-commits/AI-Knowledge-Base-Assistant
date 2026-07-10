# 🤖 AI Knowledge Base Assistant

![n8n](https://img.shields.io/badge/n8n-Automation-orange)
![Gemini](https://img.shields.io/badge/Google-Gemini-blue)
![RAG](https://img.shields.io/badge/AI-RAG-success)
![License](https://img.shields.io/badge/License-MIT-green)

An AI-powered Knowledge Base Assistant built using **n8n**, **Google Gemini**, and **Retrieval-Augmented Generation (RAG)**.
This project automates the complete lifecycle of knowledge management by collecting user questions through a public form, validating submissions, generating AI-powered tags using Google Gemini, storing structured knowledge inside n8n Data Tables, and answering future queries through a Retrieval-Augmented Generation (RAG) AI Assistant.

---

# 📸 Workflow Overview

The complete automation workflow built inside n8n.

![Workflow Overview](assets/workflow-overview.png)

---

# 🚀 Features

- 📋 Public Question & Answer Submission Form
- ✅ Email Validation
- 🤖 AI-generated Tags using Google Gemini
- 🗄️ Automatic Knowledge Base Storage
- 🔍 Retrieval-Augmented Generation (RAG)
- 💬 AI Chat Assistant
- 🧠 Conversation Memory
- ⚡ Fully Automated using n8n
- 📊 Structured Knowledge Management
- 🔄 No Custom Backend Required

---

# 📝 Question & Answer Submission Form

Users can submit their Name, Email, and Question using a public form.

Every submission enters the automation workflow for validation and AI processing.

![Question & Answer Submission Form](assets/question-answer-submission-form.png)

---

# ⚙️ Form Submission Workflow

This workflow validates the email address, generates AI-powered tags using Google Gemini, and stores the processed data inside the Knowledge Base.

![Form Submission Workflow](assets/form-submission-workflow.png)

---

# 🗄️ Knowledge Base

All validated questions, answers, metadata, and AI-generated tags are automatically stored inside an n8n Data Table for future retrieval.

![Knowledge Base](assets/knowledge-base-table.png)

---

# 🤖 RAG Chat Workflow

When a user asks a question, the AI Assistant searches the Knowledge Base, retrieves the most relevant information, and generates an accurate contextual response using Retrieval-Augmented Generation (RAG).

![RAG Chat Workflow](assets/rag-chat-workflow.png)

---

# 💬 AI Chat Demo

Example conversation with the AI Knowledge Base Assistant.

![Chat Demo](assets/chat-demo.png)

---

# 🏗️ Project Architecture

```text
                 User
                   │
                   ▼
      Question & Answer Form
                   │
                   ▼
          Email Validation
                   │
                   ▼
      Google Gemini (AI Tags)
                   │
                   ▼
     n8n Data Table (Knowledge Base)
                   │
                   ▼
      AI Agent (RAG Retrieval)
                   │
                   ▼
         AI Chat Assistant
```

---

# 📂 Project Structure

```text
AI-Knowledge-Base-Assistant/
│
├── workflows/
│   ├── form-submission-workflow.json
│   └── rag-chat-assistant.json
│
├── assets/
│   ├── workflow-overview.png
│   ├── question-answer-submission-form.png
│   ├── form-submission-workflow.png
│   ├── knowledge-base-table.png
│   ├── rag-chat-workflow.png
│   └── chat-demo.png
│
├── README.md
├── LICENSE
└── .gitignore
```

---

# 🛠️ Technologies Used

- n8n
- Google Gemini
- AI Agent
- Retrieval-Augmented Generation (RAG)
- n8n Data Tables
- JSON Workflows

---

# 📥 Installation

1. Clone this repository.
2. Import both workflow JSON files into n8n.
3. Configure your Google Gemini credentials.
4. Create the required n8n Data Table.
5. Activate both workflows.

---

# 💡 How It Works

1. User submits a question through the public form.
2. Email is validated.
3. Google Gemini generates intelligent tags.
4. The submission is stored inside the Knowledge Base.
5. The AI Assistant retrieves relevant information using RAG.
6. Context-aware answers are generated for future users.

---

# 📌 Use Cases

- Internal Company Knowledge Base
- FAQ Automation
- AI Customer Support
- Documentation Search
- Team Knowledge Sharing
- AI Help Desk

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

It helps others discover the project and supports future development.
