# WF-2: Customer Order Summarizer – n8n Workflow

## 📌 Overview

This **n8n workflow**, `WF-2: Customer Order Summarizer`, automates the process of summarizing new customer orders and emailing the summary to the relevant team. It integrates Google Sheets, OpenAI’s GPT-4o-mini, and Gmail to streamline order processing.

## 🔧 Workflow Components

### 🏗️ Core Modules

1. **📊 Google Sheets Trigger** – Monitors a Google Sheet for new customer orders.
2. **🤖 Summarizer (GPT-4o-mini)** – Processes order details and generates a summary.
3. **📧 Gmail** – Sends the summarized order details via email to the team.

## ⚙️ How It Works

1. 📑 A new order is added or updated to the Google Sheet.
2. 🔍 The **Summarizer** processes the order details and formats a structured email.
3. 📤 The email is sent to the designated recipients from the **Gmail** node.

## 🚀 Setup Instructions

- 📥 **Import the workflow** into `n8n`.
- 🔑 **Ensure Google Sheets and Gmail API credentials** are configured.
- ✅ **Activate the workflow** to start summarizing customer orders.

## 📝 Notes

- ⚠️ The workflow is **inactive by default**.
- 🛠️ Modify email recipients and sheet references as needed.
