# AI Social Automation Agent 🤖📢

An AI-powered automation system that generates engaging social media content using Google Gemini AI and automatically publishes it to LinkedIn based on topics stored in Google Sheets.

---

## 🚀 Features

* AI-powered content generation
* Automated LinkedIn post publishing
* Google Sheets-based content management
* Scheduled social media automation
* No manual copy-pasting required
* Fully automated workflow using n8n
* 100% self-hosted solution

---

## 🧠 Architecture

```text
Schedule Trigger
      │
      ▼
Google Sheets
      │
      ▼
Google Gemini AI
      │
      ▼
Content Generation
      │
      ▼
LinkedIn API
      │
      ▼
Automatic Post Publishing
```

---

## 🛠 Tech Stack

* n8n
* Google Gemini AI
* Google Sheets API
* LinkedIn API
* JSON Processing

---

## 📸 Screenshots

### 🔄 n8n Workflow

![Workflow](https://github.com/Harish-Uta17/AI-Social-Automation-Agent/blob/main/Screenshots/workflow.png?raw=true)


---

### 📊 Google Sheets Input

![Google Sheets](https://github.com/Harish-Uta17/AI-Social-Automation-Agent/blob/main/Screenshots/sheets.png?raw=true)


---

### 📢 LinkedIn Post Output

![LinkedIn Output](https://github.com/Harish-Uta17/AI-Social-Automation-Agent/blob/main/Screenshots/output.png?raw=true)


---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Harish-Uta17/AI-Social-Automation-Agent.git
cd AI-Social-Automation-Agent
```

### 2. Install n8n

Install and start n8n on your local machine or server.

### 3. Import Workflow

Import the workflow JSON file into n8n.

### 4. Configure Credentials

Add the following credentials:

* Google Gemini API Key
* Google Sheets API Credentials
* LinkedIn API Credentials

### 5. Configure Google Sheets

Create a Google Sheet containing content topics or prompts that will be used for social media post generation.

### 6. Schedule Execution

Set up a schedule trigger in n8n to automate posting at your desired frequency.

### 7. Run the Workflow

The workflow will:

* Read content topics from Google Sheets
* Generate engaging posts using Gemini AI
* Format content professionally
* Publish posts automatically to LinkedIn

---

## 📂 Project Structure

```text
AI-Social-Automation-Agent/
│
├── workflow/
│   └── AI Social Automation Agent.json
│
├── Screenshots/
│   ├── workflow.png
│   ├── sheets.png
│   └── output.png
│
├── README.md
│
└── .env.example
```

---

## 🔄 Workflow Overview

1. Schedule Trigger initiates the workflow.
2. Google Sheets provides content topics.
3. Gemini AI generates high-quality social media content.
4. Content is formatted for LinkedIn.
5. LinkedIn API publishes the post automatically.
6. The workflow repeats based on the configured schedule.

---

## 🎯 Use Cases

* Personal Branding
* LinkedIn Content Automation
* Marketing Campaigns
* Business Page Management
* Thought Leadership Content
* AI-Powered Social Media Management

---

## 🌟 Key Benefits

* Saves hours of manual content creation
* Maintains consistent posting schedules
* Generates engaging AI-powered content
* Centralized content management through Google Sheets
* Fully automated posting workflow
* Easy customization and scaling

---

## 👨‍💻 Author

**Harish Uta**
B.Tech – Data Science | AI Automation Engineer

GitHub: https://github.com/Harish-Uta17

---

## ⭐ Support

If you found this project useful, please consider giving it a **Star ⭐** on GitHub.
