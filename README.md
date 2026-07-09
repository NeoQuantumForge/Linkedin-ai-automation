# AI LinkedIn Content Automation with n8n

## Overview

This project is an end-to-end LinkedIn content automation workflow built using **n8n**, **Groq**, **Google Sheets**, **Docker**, and the **LinkedIn API**.

The workflow automatically generates professional LinkedIn posts using an AI model hosted by Groq, stores and manages the generated content in Google Sheets, and publishes the approved posts directly to a LinkedIn personal profile through the official LinkedIn API.

The goal of this project was to learn workflow automation, API integration, OAuth 2.0 authentication, and AI-assisted content generation while building a practical automation system.

---

## Features

* 🤖 AI-generated LinkedIn posts using Groq
* 🔄 Fully automated workflow built in n8n
* 📊 Google Sheets integration for content management
* 🔐 LinkedIn OAuth 2.0 authentication
* ✍️ Automatic posting to a LinkedIn personal profile
* 🐳 Docker-based deployment
* 📅 Scheduled publishing using n8n

---

## Workflow

```text
Schedule Trigger
        │
        ▼
Read Topic from Google Sheets
        │
        ▼
Generate LinkedIn Post (Groq)
        │
        ▼
Update Google Sheets
        │
        ▼
Publish to LinkedIn
```

---

## Technologies Used

* n8n
* Groq API
* LinkedIn API
* Google Sheets API
* OAuth 2.0
* Docker

---

## Screenshots

The repository includes screenshots demonstrating:

* Complete n8n workflow
* Google Sheets integration
* LinkedIn publishing node
* Successful workflow execution

---

## Security Notice

This repository intentionally **does not include**:

* n8n workflow exports
* API keys
* OAuth credentials
* Access tokens
* Client secrets
* Environment variables

These files have been excluded to protect sensitive credentials and prevent unauthorized access.

---

## What I Learned

Through this project, I gained hands-on experience with:

* Workflow automation using n8n
* AI integration using the Groq API
* OAuth 2.0 authentication with the LinkedIn API
* Google Sheets API integration
* Docker container deployment
* Designing reliable automation pipelines
* Debugging authentication and API permission issues

---

## Future Improvements

* Human approval before publishing
* Image generation for LinkedIn posts
* Multi-platform publishing (X, Facebook, Threads)
* Analytics and engagement tracking
* Automatic hashtag optimization
* Retry and failure notification system

---

## Disclaimer

This repository is intended for educational and portfolio purposes. The implementation details, screenshots, and documentation demonstrate the project's architecture and functionality without exposing sensitive credentials or private configuration.

## Screenshots

### Complete Workflow

![Workflow Overview](screenshots/workflow-overview.png)

### Google Sheets Node

![Google Sheets](screenshots/google-sheets-node.png)

### LinkedIn Node

![LinkedIn](screenshots/linkedin-node.png)

### Successful Execution

![Successful Execution](screenshots/successful-run.png)
