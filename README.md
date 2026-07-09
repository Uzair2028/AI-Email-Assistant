# AI Email Assistant

An AI-powered email assistant built with **n8n**, **Google Gemini**, and **Gmail API** to automatically read incoming emails, generate professional responses, and send replies through Gmail.

---

## Overview

This project demonstrates an intelligent email automation workflow that combines Gmail with Google's Gemini large language model (LLM). When a new email is received, the workflow analyzes the email content, generates a professional response using AI, and sends the reply automatically.

This project showcases practical AI workflow automation using a no-code/low-code platform.

---

## Features

* 📩 Automatically detects new Gmail messages
* 🤖 Uses Google Gemini to generate professional email replies
* 📧 Sends AI-generated responses through Gmail
* ⚡ End-to-end automation using n8n
* 🔒 Secure credential management through n8n credentials
* 🧩 Easy to customize for different email response scenarios

---

## Workflow

```text
Gmail Trigger
      │
      ▼
AI Agent (Google Gemini)
      │
      ▼
Gmail Send Message
```

---

## Technologies Used

* n8n
* Google Gemini
* Gmail API
* AI Agent
* Workflow Automation

---

## Project Structure

```text
AI-Email-Assistant/
│
├── workflow/
│   └── ai-email-assistant.json
│
├── screenshots/
│   ├── workflow.png
│   ├── ai-agent.png
│   └── email-reply.png
│
└── README.md
```

---

## Setup

1. Clone this repository.
2. Import the workflow JSON into n8n.
3. Configure Gmail OAuth credentials.
4. Configure your Google Gemini API credentials.
5. Activate the workflow.
6. Send a test email to verify the automation.

---

## Future Improvements

* Email classification (Personal, Client, Promotion, Spam)
* Automatic priority detection
* Multi-language email support
* Attachment summarization
* Conversation memory
* Google Sheets logging
* RAG integration for company knowledge
* Human approval before sending replies

---

## Author

**Uzair Ali**

---

## License

This project is available under the MIT License.
