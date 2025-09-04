<img width="522" height="406" alt="image" src="https://github.com/user-attachments/assets/13bf442f-f844-463e-8a02-1b783a542e8d" />


# AI-Inbound-Voice-Calling-Agent

This project is an **AI-powered appointment assistant** built with **n8n** and **Vapi**.  
It helps users check availability, book new appointments, update existing ones, and cancel them automatically.

---

## 🚀 Features
- ✅ Check calendar availability  
- 📅 Book new appointments  
- 🔄 Reschedule existing appointments  
- ❌ Cancel appointments  
- 🤖 AI-driven responses through Vapi  
- 🔗 Works with Google Calendar  

---

## ⚙️ How It Works
1. User makes a request through Vapi.  
2. The request is sent to n8n via webhook.  
3. AI Agent in n8n understands the request.  
4. Google Calendar is updated (book, update, or cancel).  
5. Response is sent back to the user in natural language.  

---

## 📂 Project Files
- `Calling Agent.json` → n8n workflow file (import this into n8n).  

---

## ▶️ Setup
1. Install [n8n](https://n8n.io/).  
2. Import the `Calling Agent.json` workflow.  
3. Connect your Google Calendar account.  
4. Add your Vapi credentials.  
5. Start the workflow and test using Vapi.  

---

## 📝 Notes
- All times are handled in **PKT timezone**.  
- Only supports booking, rescheduling, and canceling appointments.  
- Make sure Google Calendar API is enabled.  

---

## 👤 Author
Built by **Abdul Basit**.
