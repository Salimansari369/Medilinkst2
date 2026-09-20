# 🏥 MediLinks — Advanced Healthcare Portal & Appointment System (Milestones 2 & 3)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](#)
[![Node.js](https://img.shields.io/badge/Runtime-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)](#)
[![Stage](https://img.shields.io/badge/Milestone-Task%202%20%26%203%20Final-success?style=flat-square)](#)
[![Author](https://img.shields.io/badge/Author-Salim%20Ansari-blue?style=flat-square&logo=github)](https://github.com/Salimansari369)

**MediLinks** is a healthcare management portal and patient appointment booking web application. 

This repository contains **Milestone 2 & 3 (Final Release)**, introducing interactive appointment scheduling, local state persistence, validation pipelines, and a Node.js local web server.

---

## 🌟 Key Features (Final Deliverables)

* **Interactive Appointment Booking (`appointments.html`):** Patients can select consultation dates, time slots, choose specialized doctors, and input symptom descriptions.
* **Real-time Client Validation (`appointments.js`):** Strict verification of patient contact details, booking constraints, and immediate confirmation feedback.
* **Integrated Healthcare Ecosystem:** Unified experience across Home, Doctor Listings, Services, Appointment Scheduler, and Helpdesk.
* **Node.js Local Server Support (`serve.js`):** Lightweight local development server runtime for static delivery and testing.

---

## 📁 Repository Packages & Archives

| Package Archive | Description | Key Additions |
|---|---|---|
| **`medinew task3.zip`** | Milestone 2/3 development snapshot | Added `appointments.html` & `appointments.js` |
| **`medinew-final.zip`** | Complete Final Build | Integrated Node.js server (`serve.js`), refined CSS tokens, full asset package |

### Complete Package File Structure (`medinew-final.zip`):
```text
medinew-final/
├── index.html          # Main portal homepage & doctor directory
├── appointments.html   # Dedicated doctor appointment reservation interface
├── appointments.js     # Form validation, booking logic & session state
├── about.html          # Medical team, accreditations & clinic mission
├── contact.html        # Emergency numbers, map integration & feedback form
├── script.js          # Core navigation, animations & UI interactions
├── style.css           # Global modern medical design theme
└── serve.js           # Node.js local HTTP server runtime
```

---

## 🚀 Setup & Execution Guide

### Option 1: Direct Browser Launch
1. Extract `medinew-final.zip`.
2. Open `medinew-final/index.html` in your web browser.

### Option 2: Running with Node.js
```bash
# Extract the archive
unzip medinew-final.zip
cd medinew-final

# Run the local server
node serve.js
```
Navigate to `http://localhost:3000` (or the configured terminal port).

---

## 👤 Author

* **Salim Ansari**
  * GitHub: [@Salimansari369](https://github.com/Salimansari369)