# AI Customer Email Classification & Response Automation

An intelligent email automation workflow built with **n8n**, **Google Gemini**, and **Gmail**. The workflow automatically classifies incoming customer emails into predefined categories, generates AI-powered responses, and sends personalized replies—helping businesses improve response times and automate customer communication.

---

# 📌 Overview

This project demonstrates how AI and workflow automation can streamline customer email management. Incoming emails are analyzed using Google Gemini, classified into predefined categories, and automatically responded to with appropriate AI-generated messages.

The workflow is ideal for businesses looking to automate customer support, reduce manual workload, and ensure timely communication.

---

# ✨ Features

* 📧 Automatically monitors Gmail for new emails.
* 🤖 Uses Google Gemini AI to analyze email content.
* 🏷️ Classifies emails into:

  * Complaint
  * Inquiry
  * Order
* 💬 Generates intelligent responses based on the email category.
* 📬 Sends personalized replies automatically through Gmail.
* ⚡ Fully automated workflow with minimal manual intervention.
* 🔄 Easily customizable for additional email categories.

---

# 🏗️ Workflow

```text
Gmail Trigger
      │
      ▼
Receive Customer Email
      │
      ▼
Google Gemini AI
      │
      ▼
Classify Email
      │
      ▼
Switch by Category
      │
      ▼
Generate Response
      │
      ▼
Send Reply via Gmail
```

---

# 🛠️ Technologies Used

* n8n
* Google Gemini 2.5 Flash
* Gmail API
* LangChain AI Agent

---

# 📋 Prerequisites

Before running this workflow, ensure you have:

* An n8n instance
* Gmail OAuth credentials
* Google Gemini API credentials

---

# 🚀 Installation

1. Clone this repository.
2. Import the workflow JSON into your n8n instance.
3. Configure Gmail OAuth credentials.
4. Configure Google Gemini credentials.
5. Activate the workflow.
6. Send an email to the connected Gmail account.

---

# ⚙️ How It Works

1. A customer sends an email.
2. Gmail Trigger detects the new message.
3. Google Gemini analyzes the email content.
4. The email is classified as **Complaint**, **Inquiry**, or **Order**.
5. The workflow routes the request based on the detected category.
6. An AI-generated response is prepared.
7. The reply is automatically sent to the customer via Gmail.

---

# 📈 Use Cases

* Customer support automation
* Order management
* Product inquiries
* Complaint handling
* AI-powered email assistants
* Small business automation

---

# 🔮 Future Enhancements

* Sentiment analysis
* Priority-based routing
* Multi-language support
* CRM integration
* Google Sheets logging
* Slack and Microsoft Teams notifications
* Dashboard and analytics
* Attachment processing

---

# 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, submit issues, or open pull requests to improve the workflow.

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Muneeb**

<img width="1920" height="486" alt="ai email classifier and auto reply using n8n and gemini" src="https://github.com/user-attachments/assets/26cdee2d-82f2-4f0b-8491-53cbea9cf18b" />

AI Automation Developer specializing in intelligent workflow automation using **n8n**, **Google Gemini**, and modern APIs to build scalable business solutions.

---

⭐ If you found this project useful, consider giving it a star on GitHub!
