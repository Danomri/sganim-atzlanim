<div align="center">
  <img src="https://via.placeholder.com/150x150.png?text=Logo" alt="Sganim Atzlanim Logo" width="120" />

  <h1>Sganim Atzlanim (Lazy Deputies)</h1>
  <p><b>An End-to-End Military Logistics & HR Management SaaS Platform</b></p>

  <a href="https://react.dev/"><img src="https://img.shields.io/badge/Frontend-React%20(Vite)-61DAFB?style=flat-square&logo=react&logoColor=white" alt="React" /></a>
  <a href="https://tailwindcss.com/"><img src="https://img.shields.io/badge/CSS-Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" /></a>
  <a href="https://flask.palletsprojects.com/"><img src="https://img.shields.io/badge/Backend-Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask" /></a>
  <a href="https://aws.amazon.com/ec2/"><img src="https://img.shields.io/badge/Cloud-AWS%20EC2-FF9900?style=flat-square&logo=amazonaws&logoColor=white" alt="AWS EC2" /></a>
  <a href="https://developers.google.com/sheets/api"><img src="https://img.shields.io/badge/Database-Google%20Sheets%20API-34A853?style=flat-square&logo=google-sheets&logoColor=white" alt="Google Sheets API" /></a>
  
  <br />
  <br />

  **[View Live Project](http://sganim-atzlanim.com)** • 
  **[Report a Bug](#)** • 
  **[Request Feature](#)**
</div>

---

## 🎯 The Problem & The Solution
In active combat reserves, managing hundreds of soldiers, complex logistics, weapons signatures, and daily attendance is often handled via scattered WhatsApp groups and chaotic Excel sheets. 

**Sganim Atzlanim** was built to solve this. Designed and developed by an active-duty Company Commander, this platform digitizes the entire logistical and HR workflow of a military battalion. It provides real-time dashboards, role-based access control, and seamless Google Sheets integration to keep commanders focused on the mission, not on paperwork.

---

## ✨ Key Features

* **📊 Executive Dashboard:** Real-time analytics, live attendance tracking, and urgent logistics requests overview.
* **👥 HR & Platoon Management:** * Daily attendance reporting (Present / Absent / Requesting leave).
    * Interactive vacation scheduling and graphical attendance heatmaps.
* **🛡️ Weapon & Equipment Management:**
    * Digital weapon signatures and transfers between soldiers.
    * Dynamic tracking of personal combat gear (Vests, Bags, Helmets).
* **📦 Logistics Requests:** Automated system for ordering, approving, and tracking logistical supplies across different platoons.
* **🔐 Role-Based Access Control (RBAC):** Secure JWT authentication tailored for different military ranks (Admin, Battalion Commander, Company Commander, Platoon Leader, Logistics Officer).
* **🔄 Google Sheets Two-Way Sync:** Uses the Google Sheets API as a dynamic, user-friendly database backbone that allows non-technical officers to view exported data easily.

---

## 💻 Tech Stack & Architecture

### **Frontend**
* **React (Vite):** Lightning-fast build tool and modern component-based architecture.
* **Tailwind CSS:** Utility-first framework for a highly responsive, custom "Soft UI" design system.
* **React Router:** For seamless, Single Page Application (SPA) navigation.
* **Lucide React:** Clean, consistent SVG iconography.

### **Backend**
* **Python (Flask):** Lightweight, robust RESTful API routing.
* **Flask-JWT-Extended:** Secure stateless authentication.
* **Google Sheets API:** Real-time data read/write capabilities, acting as a collaborative database for unit configurations and data persistence.

### **Infrastructure & Deployment**
* **AWS EC2:** Cloud hosting for the application server.
* **Nginx:** High-performance reverse proxy routing incoming traffic to the Flask backend and serving static React files.

---

## 📸 Sneak Peek

> **Note to Recruiters:** You can explore the platform's UI without military credentials using the built-in **Demo Mode**.

<div align="center">
  <img src="https://github.com/Danomri/sganim-atzlanim/blob/main/assets/dashboard.png?raw=true" alt="Dashboard Screenshot" width="80%" />
  <br/>
  <i>Command Dashboard - Providing a bird's-eye view of battalion readiness.</i>
</div>

---

## 🚀 Live Demo & Access

The application is deployed and ready for inspection. You can interact with the full feature set using the Guest Access:

* **Live Link:** [http://sganim-atzlanim.com](http://sganim-atzlanim.com)
* **Access Method:** Click the **"Demo Mode"** button on the login screen to enter as a Battalion Commander.

---

## 🏗️ System Architecture

This project follows a modern Full-Stack architecture designed for reliability and ease of deployment:



1. **Frontend:** Developed with **React** and **Tailwind CSS** for a responsive, high-performance user interface.
2. **Backend:** A **Flask (Python)** RESTful API handles authentication (JWT), logic, and data processing.
3. **Storage:** A dual-layer approach using **SQLite** for local session data and **Google Sheets API** for real-time, collaborative unit data management.
4. **Deployment:** Hosted on **AWS EC2** using **Nginx** as a reverse proxy.

> **Privacy Note:** The source code is maintained in a private repository to protect proprietary logistics logic. I am happy to discuss the codebase and technical challenges in detail during an interview.
