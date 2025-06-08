# 📬 Email Automation + Personal Email Assistant (n8n Workflow Suite)

### 🧠 Overview
Two powerful, modular n8n workflows that team up to make your email life hands-free and smart. One listens, one replies — together, they’re the duo you didn’t know you needed.

---

## ⚙️ Workflow 1: Personal Email Assistant

🧾 **Purpose**: A Telegram-triggered agent that reads your commands and delegates tasks to the Email Automation workflow.

📌 **Highlights**:
- Telegram-based interaction with a personal AI assistant.
- Memory-powered via Simple Memory node.
- Uses Google Sheets for record lookups and stores.
- Triggers external workflows using `Call n8n Workflow` tool.

🖼 **Workflow Preview**:
![Personal Assistant Workflow](/Personal%20Email%20Assistant/Personal_Assistant.png)

---

## ⚙️ Workflow 2: Email Automation

🧾 **Purpose**: Executes smart email replies by analyzing threads using GPT and crafting responses from context.

📌 **Highlights**:
- Executes when triggered by the Personal Assistant.
- Fetches and understands Gmail threads.
- Writes AI-generated replies via OpenAI Chat Model.
- Returns clean response data to the calling workflow.

🖼 **Workflow Preview**:
![Email Automation Workflow](/Personal%20Email%20Assistant/Email_Automation.png)

---

## 🔗 How They Work Together

1. You text a command to your **Personal Assistant** via Telegram.
2. It pulls your intent and memory, then calls the **Email Automation** workflow if needed.
3. The **Email Automation** agent reads your inbox, drafts a reply using GPT, and returns the response.
4. Your assistant updates you on Telegram like a boss.

---

## 🛠 Tech Stack
- OpenAI Chat Model (GPT-4)
- Gmail API (Send + Fetch)
- Telegram Bot API
- n8n Agent + Memory nodes
- Google Sheets (as simple DB)

---

## 🤯 Why It's Cool
Because replying to emails manually is so 2023. Automate it, own it, and make it sound like you — all from Telegram.

