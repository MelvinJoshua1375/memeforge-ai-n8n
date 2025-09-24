# MemeForge AI (n8n Workflow)

MemeForge AI is an automated workflow built with [n8n](https://n8n.io/) that generates memes dynamically using Telegram, Imgflip API, and an LLM for template and caption selection.  

---

## Features
- Telegram bot integration — users send a message, and a meme comes back.  
- Dynamic meme template selection using LLM suggestions.  
- Fallback templates in case no match is found.  
- Caption generation and splitting into multiple boxes.  
- Fully automated end-to-end meme generation.  

---

## Notes
- Telegram requires a public HTTPS webhook. Use [ngrok](https://ngrok.com/) or a reverse proxy for local testing.  
- This project is for fun and learning automation. Not for production use.  
