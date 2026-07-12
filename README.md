#  AI Customer Enquiry Automation using n8n, Google Gemini & Twilio WhatsApp

![n8n](https://img.shields.io/badge/n8n-Automation-orange?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Google-Gemini-blue?style=for-the-badge)
![Twilio](https://img.shields.io/badge/Twilio-WhatsApp-red?style=for-the-badge)
![Google Sheets](https://img.shields.io/badge/Google-Sheets-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

---

##  Overview

This project is an **AI-powered Customer Enquiry Automation System** built using **n8n**, **Google Gemini AI**, **Google Sheets**, and **Twilio WhatsApp API**.

The workflow automatically collects customer details, stores them in Google Sheets, and sends an instant WhatsApp confirmation message without any manual intervention.

---

#  Features

 AI-powered customer interaction

 Automated workflow using n8n

 Customer enquiry collection

 Google Sheets integration

 WhatsApp confirmation messages

 No manual data entry

 Easy to customize for any business

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
|  Google Gemini AI | AI Responses |
|  n8n | Workflow Automation |
|  Google Sheets | Database |
|  Twilio WhatsApp API | WhatsApp Notifications |

---

#  Workflow

```text
Customer Chat
      │
      ▼
Google Gemini AI
      │
      ▼
Collect Customer Details
      │
      ▼
Google Sheets
      │
      ▼
Twilio WhatsApp
      │
      ▼
Confirmation Message Sent
```

---

#  Project Structure

```
AI-Customer-Enquiry-Automation
│
├── workflow.json
├── README.md
├── images
│   ├── workflow.png
│   ├── chatbot.png
│   ├── google-sheet.png
│   └── whatsapp-message.png
```

---

#  Project Screenshots

## Workflow

<img width="940" height="381" alt="image" src="https://github.com/user-attachments/assets/de892e05-505d-4c14-b6e0-855164b21334" />

## Google Sheet

<img width="940" height="308" alt="image" src="https://github.com/user-attachments/assets/65ccdfaa-2588-45e3-86a3-2eccbe8dc834" />


<img width="940" height="129" alt="image" src="https://github.com/user-attachments/assets/9c9c99a5-e0cc-47e3-9e5c-20c151f1874b" />

---

## WhatsApp Confirmation
<img width="706" height="864" alt="image" src="https://github.com/user-attachments/assets/f28eaaa0-80c0-4007-859f-899335604a6b" />

---

#  How It Works

### STEP 1

Customer starts a conversation.

↓

### STEP 2

Google Gemini AI understands the request.

↓

### STEP 3

The AI collects:

- Name
- Phone Number
- Email
- Requirement

↓

### STEP 4

Customer information is automatically stored in Google Sheets.

↓

### STEP 5

Twilio sends an instant WhatsApp confirmation message.

---

#  Business Benefits

- Saves Time
- Eliminates Manual Data Entry
- Improves Customer Experience
- Automated Lead Collection
- Instant WhatsApp Notifications
- Easy to Scale

---

#  Future Enhancements

-  Appointment Booking
-  Email Notifications
-  CRM Integration
-  Multi-language Support
-  RAG Knowledge Base
-  Analytics Dashboard

---

#  Getting Started

1. Clone this repository
2. Import `workflow.json` into n8n
3. Configure:
   - Google Gemini API
   - Google Sheets credentials
   - Twilio credentials
4. Execute the workflow
5. Test the chatbot

---

# 👩‍💻 Author

**Divyanshi Sharma**

MBA (AI & Data Science)

 GitHub: https://github.com/divaaasharma

 Passionate about AI Automation, Data Analytics, AI Agents, and Workflow Automation.

---

##  If you found this project useful, don't forget to star the repository!
