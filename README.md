# 📬 LLM-Powered Email Summarizer to Discord (n8n Workflow)

This project is an automation workflow built using [n8n](https://n8n.io/) that connects **Gmail**, **Google Gemini LLM**, and **Notion**. Its goal is to **read specific emails**, summarize them using a **Large Language Model**, and **send the summarized content to a notion page** — all automatically.

---

## 🔧 Technologies Used

- **n8n** – Low-code workflow automation tool  
- **Gmail Trigger** – Detects new emails from specific sender(s)  
- **Google Gemini Chat Model** – Summarizes the content of the email  
- **Custom Code Node (JavaScript)** – Formats and prepares output  
- **Notion Integration** – Posts the summary to a Notion page  

---

## 🔁 Workflow Overview

1. **Gmail Trigger**: Detects new emails from a predefined sender.
2. **Filter Node**: Ensures only relevant emails are passed through.
3. **Get Message**: Retrieves the full content of the email.
4. **LLM Chain**: Sends email content to Google Gemini for summarization.
5. **Code Node**: Formats the summarized text for display.
6. **Notion Node**: Posts the result to a specified Notion Page.

---

## 📌 Use Case

This project is ideal for:
- Teams managing **shared inboxes** who want quick overviews in real-time.
- **Automating updates** from high-traffic sources (e.g., reports, alerts).
- Experimenting with **LLM integration in everyday workflows**.

---

## 🖼 Screenshot

![n8n Workflow][(https://github.com/aaa44623/LLM-Powered-Email-Summarizer-to-Discord-n8n-Automation-/blob/main/CaptureUpdatedN8nNew.PNG)]

---


## 📣 Author

**Ahmed Al Balushi**  
Database Developer | Technical Consultant | AI Automation Enthusiast  
[LinkedIn](https://linkedin.com/in/ahmed-al-balushi-31775b146) • [GitHub](https://github.com/aaa44623)

---

## 🧠 Future Enhancements

- Add sentiment analysis before sending summary  
- Integrate with Telegram or Slack  
- Archive original email summaries in Notion or Google Sheets  
