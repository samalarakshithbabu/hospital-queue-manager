# 🏥 Hospital Queue Manager

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?logo=javascript)
![Node.js](https://img.shields.io/badge/Node.js-18-green?logo=node.js)
![License](https://img.shields.io/badge/License-MIT-green)

**Patient Queue Management with Priority Levels**

[![View Demo](https://img.shields.io/badge/View-Demo-blue)]()
[![Report Issue](https://img.shields.io/badge/Report-Issue-red)](https://github.com/samalarakshithbabu/hospital-queue-manager/issues)

</div>

---

## 🚀 Executive Summary

A **simple hospital queue management web application** to register patients, prioritize them based on emergency level, and manage check-ins and check-outs efficiently.

### What It Does

```mermaid
graph LR
    A[Patient Check-In] --> B[Priority Assignment]
    B --> C[Queue Management]
    C --> D[Treatment]
    D --> E[Checkout]
    
    B --> B1[Critical]
    B --> B2[Moderate]
    B --> B3[Normal]
```

---

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| **Patient Check-In** | Name, emergency level, symptoms |
| **Queue Display** | Table view of current patients |
| **Priority Levels** | Critical, Moderate, Normal |
| **Checkout** | Remove patients after treatment |
| **Modular JS** | Reusable counter module |

---

## 🛠️ Technology Stack

| Component | Technology | Purpose |
|-----------|------------|---------|
| **Frontend** | HTML, CSS, Vanilla JS | UI |
| **Backend** | Node.js API | Data handling |
| **Modules** | Modular JavaScript | Code organization |

---

## 📁 Project Structure

```
hospital-queue-manager/
├── index.html       # Main HTML page
├── style.css        # Styling
├── main.js          # Core logic
├── counter.js       # Reusable counter module
├── server.js        # Backend server
├── package.json     # Node.js dependencies
└── README.md
```

---

## 🛠️ Installation

### Prerequisites
- Node.js 14+
- npm

### Setup
```bash
npm install
node server.js
# Expects API at http://localhost:3000
```

---

## ⚠️ Limitations

| Limitation | Description |
|------------|-------------|
| **Backend API** | Assumes external API |
| **Database** | No persistence (in-memory) |
| **Authentication** | No user auth |

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**SAMALA RAKSHITH BABU**

- 📧 Email: samalarakshithbabu7@gmail.com
- 💼 LinkedIn: [samala-rakshith-babu](https://www.linkedin.com/in/samala-rakshith-babu/)
- 🐙 GitHub: [samalarakshithbabu](https://github.com/samalarakshithbabu)