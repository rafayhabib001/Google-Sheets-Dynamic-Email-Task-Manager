# 📧 Google Sheets to Gmail Automation (n8n)

## 🔹 Overview

This n8n workflow automatically sends an email whenever a new row is added to a Google Sheet.

## ⚙️ How It Works

1. Google Sheets Trigger watches for new rows
2. When a new row is added
3. Gmail node sends an email to the specified address

## 📥 Required Fields in Google Sheet

* `name` → User name
* `email` → Recipient email
* `task` → Task description

## 🛠 Setup Instructions

1. Import the workflow into n8n
2. Add your Google Sheets credentials
3. Add your Gmail credentials
4. Replace `YOUR_GOOGLE_SHEET_ID` with your actual sheet ID
5. Activate the workflow

## 💡 Use Case

Useful for:

* Task assignment systems
* Team notifications
* Simple automation projects

## ⚠️ Note

This is a safe template. No real credentials or IDs are included.
