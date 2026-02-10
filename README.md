# 🎓 Academic Attendance Portal
### GVP AI Hackathon 2026 Submission

A modern, secure, and efficient attendance tracking system designed for educational institutions. This application streamlines the attendance process using **QR Codes** and **Real-Time Role-Based Dashboards**, eliminating manual paperwork.

![Status](https://img.shields.io/badge/Status-Complete-success)
![Tech](https://img.shields.io/badge/Tech-React_%7C_Tailwind-blue)

---

## 🚀 Key Features

### 👨‍🏫 For Teachers
*   **Secure Login**: Dedicated portal for faculty.
*   **Generate Sessions**: Create unique, time-bound attendance sessions instantly.
*   **QR Code Display**: Projects a large QR Code (and numeric code) for students to scan.
*   **Live Monitoring**: See the number of active students and attendance logs in real-time.
*   **Student Management**: Add, remove, and view student profiles and attendance percentages.

### 👨‍🎓 For Students
*   **Easy Access**: Login with Roll Number.
*   **Quick Check-in**: Mark attendance by entering the unique session code displayed by the teacher.
*   **Performance Tracking**: View personal attendance history and shortage warnings (<75%).
*   **Mobile Friendly**: Fully responsive design for use on phones or laptops.

---

## 🛠️ How to Run

### Option 1: Quick Start (Standalone) ⚡
We have compiled the entire application into a **single HTML file** for easy portability and testing. No installation required!

1.  Navigate to the root folder.
2.  Open **`attendance_system.html`** in any modern web browser (Chrome, Edge, Firefox).
3.  The app will load instantly with all features active.

### Option 2: Developer Mode (Source Code) 👨‍💻
If you want to edit the source code or build the React project:

1.  Ensure **Node.js** is installed.
2.  Open a terminal in the project folder.
3.  Run the following commands:
    ```bash
    npm install
    npm run dev
    ```
4.  Open the local server URL (usually `http://localhost:5173`).

---

## 🔐 Demo Credentials

To test the system efficiently, use these pre-configured accounts:

| Role | Username / Roll No | Password | Capabilities |
| :--- | :--- | :--- | :--- |
| **Teacher** | `admin` | `123` | Create Sessions, Manage Students |
| **Student** | `101` | `123` | Mark Attendance, View Stats |
| **Student** | `102` | `123` | Mark Attendance, View Stats |

> **Note**: Data is persisted in your browser's **LocalStorage**. If you refresh the page, your added students and attendance records remain saved!

---

## 💻 Tech Stack

*   **Frontend Library**: React 18
*   **Styling**: Tailwind CSS (Utility-first framework)
*   **Icons**: Lucide React
*   **Utilities**: QR Code Generation, LocalStorage DB Simulation
*   **Font**: Inter (Google Fonts)

---

## 📝 Project Structure

```
GVP_AI_HACKATHON_2026/
├── attendance_system.html  # 🌟 RUN THIS FILE (Standalone App)
├── src/
│   ├── components/         # React Components (Auth, Dashboards)
│   ├── utils/              # Database Logic (db.js)
│   ├── App.jsx             # Main Entry Point
│   └── index.css           # Tailwind Styles
├── public/                 # Static Assets
└── README.md               # Documentation
```

---

*Verified for GVP AI Hackathon 2026*
