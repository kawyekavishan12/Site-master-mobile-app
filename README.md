# 🏗️ SiteMaster - Construction Site Attendance & Payroll Manager

A lightweight, responsive, and mobile-friendly web application tailored for **Construction Site Engineers and Supervisors** to seamlessly manage daily crew attendance, overtime (OT) hours, cash advances (Sub), and weekly/monthly payroll calculations.

🔗 **Live Demo:** [anuruddha-cons.netlify.app](https://anuruddha-cons.netlify.app)

---

## ✨ Features

- **📊 Live Site Dashboard:** Real-time headcount of workers present, half-days, today's OT hours, and cash advances issued.
- **📅 Quick Attendance Tracker:** Mark Present (Full Day), Half-Day, or Absent with quick OT hour adjustment (+0.5h / -0.5h).
- **💵 Cash Advances (Sub) Tracker:** Log daily cash advances given on-site with notes and timestamps.
- **📑 Automated Payroll Calculation:** Automatically computes:
  - Base wages (Days Worked × Daily Rate)
  - Overtime pay (OT Hours × OT Rate)
  - Deductions (Cash Advances)
  - **Net Payable Wage**
- **🖨️ Printable Payslips & Summary Sheets:** Generates clean, printer-friendly individual payslips with signature lines and complete weekly site payroll sheets.
- **📲 WhatsApp Summary Generator:** One-click generation of formatted payroll summaries ready to send via WhatsApp.
- **💾 100% Offline Capable & Data Backup:** Saves data locally on-device (`localStorage`) with JSON backup export/import capabilities.

---

## 🛠️ Built With

- **HTML5 & CSS3**
- **Tailwind CSS** (via CDN)
- **Vanilla JavaScript** (Zero dependencies)
- **Lucide Icons**
- Hosted on **Netlify**

---

## 🚀 Getting Started

1. Clone or download this repository:
   ```bash
   git clone https://github.com/<your-username>/SiteMaster.git
   ```
2. Simply double-click `index.html` to open it in any modern web browser (Chrome, Edge, Safari, Firefox).
3. No build tools or package installations required!

---

## 📱 Mobile App Experience (PWA)

To use this like a native mobile app:
1. Open the live link in your phone's browser (Safari or Chrome).
2. Tap the browser menu and select **"Add to Home Screen"** or **"Install App"**.
3. Launch it directly from your home screen anytime on the job site!
