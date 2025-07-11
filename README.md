# 📬 Automatic Email Delivery System using n8n

![n8n-logo](https://n8n.io/images/n8n-logo.png)

> A zero-code automation workflow to send personalized emails using data from Google Sheets — powered by n8n, Google Sheets, and Gmail API.

## 🚀 Project Overview

This project automates the task of sending customized emails with **zero manual intervention**. Built using the [n8n](https://n8n.io/) open-source workflow automation tool, this workflow allows anyone to:

✅ Read user data (Name & Email) from **Google Sheets**  
✅ Send **personalized emails** using the **Gmail API**  
✅ Trigger everything with a **single click** in the n8n UI

---

## 📸 Demo Snapshots

| Google Sheet Sample | Workflow in Action | Email Output |
|---------------------|---------------------|--------------|
| ![Sheet](screenshots/google-sheet-sample.png) | ![n8n Workflow](screenshots/n8n-workflow.png) | ![Email](screenshots/email-output.png) |

> *Note: Screenshots are inside the `/screenshots` folder.*

---

## 🛠 Tech Stack

- ✅ [n8n (self-hosted)](https://n8n.io/)
- ✅ Google Sheets API
- ✅ Gmail API
- ✅ Node.js (for custom nodes, if extended)

---

## 🧩 How It Works

1. **Trigger**: Manual execution from n8n or webhook
2. **Google Sheets Node**: Fetch name and email addresses
3. **Gmail Node**: Compose and send personalized emails
4. **Done**! 🎉

---

## 🔧 Setup Instructions

### 1. Clone this Repository

```bash
git clone https://github.com/your-username/automatic-email-n8n.git
cd automatic-email-n8n
