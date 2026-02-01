# Telegram + Lovable Appointment System (n8n)

This project demonstrates an end-to-end appointment scheduling system using:
- Telegram Bot
- Lovable frontend
- n8n workflow automation

---

## 🚀 Task 1: Telegram Integration

### Description
A Telegram bot is integrated with n8n to handle user conversations and appointment intent detection.

### Features
- Telegram Trigger replaces chat trigger
- Handles user messages via Telegram
- Detects appointment requests
- Responds dynamically using Telegram nodes

### Files
- `task-1-telegram/workflow.json`
- Screenshots in `task-1-telegram/screenshots/`

---

## 🖥️ Task 2: Lovable Frontend + Webhook

### Description
A frontend appointment booking form is created using Lovable and connected to n8n via a webhook.

### Features
- User fills appointment form on Lovable UI
- Data sent to n8n webhook (POST request)
- n8n processes data and sends confirmation email
- Respond to Webhook returns success response

### Files
- `task-2-lovable/webhook-workflow.json`
- Screenshots in `task-2-lovable/screenshots/`

---

## 🧠 Architecture Overview

Telegram / Lovable → n8n Webhook → Processing → Email Notification → Response

---

## ✅ Status
- Task 1 Completed
- Task 2 Completed
- End-to-End flow tested successfully
