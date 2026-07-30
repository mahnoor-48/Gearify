<div align="center">

# 🚗 Gearify

### Automotive Performance & Maintenance System(APMS0

**A full-stack platform that digitizes vehicle workshop operations — from intake to invoice.**

[![Made with Flask](https://img.shields.io/badge/Backend-Flask-000000?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License](https://img.shields.io/badge/License-MIT-6A5ACD?style=for-the-badge)](#-license)

[Overview](#-overview) •
[Features](#-key-features) •
[Architecture](#️-system-architecture) •
[Setup](#️-installation--setup) •
[Roadmap](#-future-improvements) •
[Author](#-author)

</div>

---

## 📌 Overview

**Gearify** replaces manual, paper-based workshop management with a single, organized digital workflow. It gives workshop owners and staff a centralized place to manage **vehicles, customers, service history, billing, and receipts** — no more scattered notebooks or spreadsheets.

Built with **Flask, Python, HTML, CSS, and JavaScript**, Gearify is a practical, full-stack demonstration of backend architecture, structured data management, authentication, and clean, responsive UI design — applied to a real, everyday industry problem.

> Not just another CRUD app — Gearify models an actual business workflow, end to end.

---

## ✨ Key Features

<table>
<tr>
<td width="50%" valign="top">

### 🔐 Secure Authentication
- User registration and login system
- Protected, session-based access
- Role-based access management

### 🚘 Vehicle Management
- Add and manage vehicle records
- Digitally store vehicle information
- Track complete vehicle service history

### 🛠 Maintenance Management
- Log every service performed
- Maintain a full repair history
- Monitor vehicle performance over time

</td>
<td width="50%" valign="top">

### 💳 Automated Billing
- Generate service invoices
- Auto-calculate maintenance costs
- Maintain organized billing records

### 🧾 Digital Receipts
- Generate digital service receipts
- Improve transparency between workshop & customer

### 📊 Data Management
- Structured, JSON-based data storage
- Cleanly organized customer, vehicle & service records

</td>
</tr>
</table>

---

## 🏗️ System Architecture

```
        User Interface
              │
              ▼
   HTML + CSS + JavaScript
              │
              ▼
        Flask Backend
              │
              ▼
      Data Storage Layer
       (JSON Database)
```

---

## 🛠️ Technologies Used

| Layer | Stack |
|---|---|
| **Frontend** | HTML5 · CSS3 · JavaScript |
| **Backend** | Python · Flask |
| **Data Handling** | JSON-based storage |
| **Dev Tools** | Git & GitHub · Visual Studio Code |

---

## 📂 Project Structure

```
GEARIFY
│
├── app.py
├── requirements.txt
│
├── templates/
├── static/
│
├── data/
│   ├── users.json
│   ├── cars.json
│   ├── history.json
│   └── prices.json
│
└── README.md
```

---

## ⚙️ Installation & Setup

**1. Clone the repository**
```bash
git clone https://github.com/mahnoor-48/Gearify.git
```

**2. Navigate to the project folder**
```bash
cd Gearify
```

**3. Install dependencies**
```bash
pip install -r requirements.txt
```

**4. Run the application**
```bash
python app.py
```

**5. Open in your browser**
```
http://127.0.0.1:5000
```

---

## 🎯 Project Objectives

Gearify demonstrates how software engineering principles can be applied to solve a real-world automotive service problem. It focuses on:

- ✔ Digital transformation of workshop management
- ✔ Efficient, structured data organization
- ✔ Improved service tracking and visibility
- ✔ Automation of repetitive administrative work
- ✔ User-friendly, intuitive software design

---

## 🚀 Future Improvements

- [ ] ☁️ Cloud database integration
- [ ] 🤖 AI-based vehicle maintenance prediction
- [ ] 📅 Online appointment scheduling
- [ ] 📈 Admin analytics dashboard
- [ ] 📱 Mobile application version

---

## 👩‍💻 Author

**Mahnoor**
Data Science Student · Full-Stack Development, Software Engineering & Intelligent Systems

[![GitHub](https://img.shields.io/badge/GitHub-mahnoor--48-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/mahnoor-48)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/mahenur-murtaza-a46397343)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:mahnoor16307@gmail.com)

---

## ⭐ Why Gearify?

Gearify isn't just a CRUD application — it's a practical, industry-oriented solution combining **backend logic**, **frontend design**, and **real-world business workflow automation** into one cohesive system.

If you found this project useful or interesting, **consider giving it a star** — it genuinely helps! ⭐

