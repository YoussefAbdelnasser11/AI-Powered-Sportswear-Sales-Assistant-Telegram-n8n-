# AI-Powered-Sportswear-Sales-Assistant-Telegram-n8n-

# 🤖 AI-Powered Sportswear Sales Assistant (Telegram + n8n)

This project is an AI-driven sales automation system built for a sportswear business in Egypt. It uses **n8n**, **Telegram**, **OpenAI**, and **Google Sheets** to provide a seamless customer experience — from chat to checkout.

## 💼 Business Purpose

Designed to streamline the order process, reduce manual tasks, and improve customer engagement through an intelligent conversational interface.

## ⚙️ Features

- Chat-based shopping assistant via Telegram
- AI-powered responses using OpenAI (ChatGPT)
- Product search by category, size, and color
- Step-by-step order collection
- Auto-logging orders to Google Sheets
- Email confirmation to customer via Gmail
- Fully no-code, scalable, and extendable

## 📦 Tech Stack

- [n8n](https://n8n.io) – Workflow automation
- [Telegram Bot](https://core.telegram.org/bots)
- Google Gemini
- Google Sheets (Product + Order storage)
- Gmail Node (for transactional emails)

## 📊 Example Sheets

- `product_catalog_sample.csv` – Example of product data
- `customer_orders_sample.csv` – Format used for order storage

## 💬 Example Use Case

> Customer: *“I want a black hoodie in size L.”*  
> Bot: *“Great! Black hoodie in size L is available for 500 EGP. Shall I place the order?”*

Once the customer confirms, the bot:
1. Collects personal and shipping info
2. Saves the order
3. Sends confirmation email

## 📸 Screenshots

![Telegram Chat](./screenshots/telegram_chat.png)  
![Workflow View](./screenshots/n8n_workflow_view.png)

## 📁 Files

- `workflow.json` – n8n workflow export
- `email_template.html` – HTML used for confirmation email

## 📌 Author

[Yousef Abdelnasser](https://www.linkedin.com/in/youssef-abdalnasser-33705b262/) – AI & Automation Developer  
Open to collaboration and feedback!

#ai-sportswear-assistant/
│
├── README.md
├── workflow.json            ← ملف n8n export
├── product_catalog_sample.csv
├── customer_orders_sample.csv
├── email_template.html
└── screenshots/
    ├── telegram_chat.png
    ├── n8n_workflow_view.png
