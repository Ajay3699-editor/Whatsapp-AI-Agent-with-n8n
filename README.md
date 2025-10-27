# 🤖 AI WhatsApp Chatbot using n8n + Google Gemini + SerpAPI

An intelligent **AI-powered WhatsApp Chatbot** built using **n8n automation**, **Google Gemini Chat Model**, and **SerpAPI**.  
This chatbot can **understand natural language**, **search live data from Google**, and **reply instantly on WhatsApp** — all in a fully automated workflow.

---

## 🧠 Workflow Overview

Below is the actual n8n workflow used in this project 👇  

![Workflow Screenshot](https://github.com/Ajay3699-editor/Whatsapp-AI-Agent-with-n8n/blob/98c2a80c873e5c17b955ce292cd67455fc4ff647/Screenshot%202025-10-27%20101705.png)

### 🔄 Workflow Structure

---

## ✨ Features

- 💬 Real-time WhatsApp message automation  
- 🧠 Smart AI agent powered by **Google Gemini**  
- 🔍 Integrated with **SerpAPI** for real-time web search  
- ⚙️ Fully no-code automation with **n8n**  
- ☁️ Easy customization and scalability  
- 🔄 Dynamic two-way conversation support  

---

## 🧩 Tech Stack

| Tool / Platform | Purpose |
|------------------|----------|
| **n8n** | Automation workflow tool |
| **Google Gemini Chat Model** | AI reasoning and response generation |
| **SerpAPI** | Live Google Search API integration |
| **WhatsApp Cloud API** | Send & receive messages |
| **HTTP Request Node** | Communication bridge between APIs |

---

## ⚙️ Setup Instructions

### 1️⃣ Prerequisites

- **n8n account** (local or cloud)  
- **Google Gemini API Key**  
- **SerpAPI Key**  
- **WhatsApp Cloud API credentials**  
- Basic knowledge of n8n workflow nodes  

---

### 2️⃣ Steps to Build the Workflow

1. **Create Workflow in n8n**  
   Open n8n and start a new workflow.  

2. **Add WhatsApp Trigger Node**  
   Receives messages from WhatsApp via webhook.  

3. **Add AI Agent Node**  
   - Connect the **Google Gemini Chat Model** to it as the main model.  
   - Connect the **SerpAPI** node as a tool for real-time search.  
   - (Optional) Add memory to maintain short-term context.  

4. **Add Send Message Node**  
   Sends the AI-generated reply back to the user on WhatsApp.  

5. **Deploy the Workflow**  
   Copy your webhook URL from the WhatsApp Trigger node and paste it into your **WhatsApp Cloud API webhook settings** (Meta Developer Portal).  

6. **Test Your Chatbot**  
   Send a message from your WhatsApp → the AI Agent replies instantly.

---

## 🧠 Use Cases

- 🧾 AI customer support assistant  
- 🧠 Smart personal WhatsApp assistant  
- 🔍 Information retrieval bot using SerpAPI  
- 🎓 Educational Q&A chatbot  
- 🔔 Automated business reply bot  

---

## 🚀 Future Enhancements

- Add OpenAI or Claude support for response comparison  
- Store chat history in a database (MongoDB or Airtable)  
- Support multiple WhatsApp numbers  
- Add voice message response  

---

## 💡 Author

**Ajaybabu Kante**  
> “Built an AI Agent that makes WhatsApp smarter — powered by n8n, Gemini, and SerpAPI.”

---

## ⭐ Support

If you like this project, please ⭐ the repo and share it with others who love **AI + Automation**.  
Your support helps improve open-source projects like this 🚀

---


