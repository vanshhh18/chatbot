# 🤖 AI Chatbot using n8n + HTML

A simple **AI-powered chatbot** built with **HTML, CSS, JavaScript, and n8n automation**.
This project demonstrates how to connect a frontend chat interface with an AI backend using webhooks.

---

## 🚀 Live Demo

You can try the chatbot here:

**🌐 Website:**
https://vanshhh18.github.io/chatbot

---

## ✨ Features

* 💬 ChatGPT-style chat interface
* ⚡ Real-time responses using **n8n AI Agent**
* 🌍 Works on **any device (mobile, laptop, tablet)**
* ☁️ Backend hosted online for **24/7 availability**
* 🔗 Simple **Webhook integration**
* 🧩 Easy to embed in other websites

---

## 🏗️ Architecture

User sends message → Website → n8n Webhook → AI Agent → Response back to website

```
User Device
     ↓
Chatbot Website
     ↓
Webhook API
     ↓
AI Agent (n8n)
     ↓
Response to Chat UI
```

---

## 📂 Project Structure

```
chatbot/
│
├── index.html        # Chatbot UI
├── chatbot.json      # n8n workflow
└── README.md         # Project documentation
```

---

## ⚙️ Setup Guide

### 1️⃣ Import Workflow

1. Open your n8n dashboard
2. Go to **Workflows → Import**
3. Upload the `chatbot.json` file
4. Activate the workflow

---

### 2️⃣ Get Webhook URL

After activating the workflow, copy your webhook URL:

```
https://your-n8n-server.com/webhook/chatbot
```

---

### 3️⃣ Update HTML File

Open **index.html** and replace the webhook URL:

```javascript
fetch("https://your-n8n-server.com/webhook/chatbot")
```

---

### 4️⃣ Deploy Website

You can deploy the frontend using:

* GitHub Pages
* Netlify
* Vercel

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript
* n8n Automation
* Webhooks

---

## 🎯 Use Cases

* AI website assistant
* Customer support chatbot
* Personal AI projects
* Automation demos
* Portfolio projects

---

## 📌 Future Improvements

* Typing animation
* Streaming responses
* Memory support
* Voice input
* Floating chat widget

---

## 👨‍💻 Author

Created by **Vansh**

If you like this project, consider giving it a ⭐ on GitHub!

---

## 📜 License

This project is open-source and free to use.
