# 🧠 HR Onboarding System – Intelligent Odoo App | Hackathon 2025

> 🎯 **Team: Script Squad**

 |   Member   | Role                 | Responsibility                                        |
 | ---------- | -------------------- | ----------------------------------------------------- |
 |   Samir    | Frontend Developer   | Designed QWeb UI, built responsive onboarding screens |
 |   Ritu     | Management & QA      | Defined onboarding workflows, testing & documentation |
 |   Vishwa   | Supabase Integration | File upload logic, API integration                    |
 |   Mahek    | Backend Developer    | ORM models, business logic, automation engine         |
 
> 👨‍💻 Built for the Future of Enterprise Automation

> 🛠️ Tech Stack: Odoo 16 · Python · PostgreSQL · Supabase · REST APIs

---

## 🔥 TL;DR (One-Line Pitch)

`HR Onboarding System` is a plug-and-play Odoo module that automates employee onboarding with smart checklists, task delegation, document tracking, and cross-department coordination — reducing manual HR work and improving new hire experience.

---

## 🚩 Problem Statement

Most organizations struggle with manual and fragmented onboarding processes. HR needs to coordinate across multiple departments, manually assign tasks, and send email reminders. This leads to delays, compliance issues, and frustrated new hires.

---

## 💡 Our Solution

We developed an **automated HR Onboarding System** in Odoo 16 that:
- Automatically generates checklists based on role or department
- Assigns tasks to IT, Admin, and HR teams
- Tracks onboarding progress in real-time
- Lets employees upload and verify documents
- Sends automated email + in-app alerts

---

## ✨ Core Features

| Feature                     | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| 🧾 Checklist Templates       | Create reusable onboarding task flows per role                             |
| 🏢 Department Task Routing   | Auto-assign tasks to HR, IT, Admin                                          |
| 📥 Document Upload/Verify   | Employees upload docs; Admin approves                                       |
| 📊 Progress Dashboard       | Visual tracker for onboarding status                                        |
| 📬 Smart Notifications      | Alerts via email + in-app for due/overdue tasks                            |
| 🌐 Web Portal Access        | Employee self-service access (optional)                                     |

---

## 🧱 Module Architecture

```plaintext
        ┌────────────────────┐
        │  New Employee Added│
        └─────────┬──────────┘
                  ↓
      ┌────────────────────────────┐
      │ Checklist Auto-Generated   │◄────────────┐
      │ Based on Role/Department   │             │
      └─────────┬──────────────────┘             │
                ↓                                │
  ┌────────────────────────────┐                 │
  │ Tasks Assigned Automatically│                │
  │ to IT / Admin / HR Teams   │                 │
  └─────────┬──────────────────┘                 │
            ↓                                    │
 ┌──────────────────────────────┐                │
 │ Employees Upload Documents   │                │
 │ via Portal or Backend Access │                │
 └─────────┬────────────────────┘                │
           ↓                                     │
 ┌─────────────────────────────────────────────┐ 
 │ Admin/HR Reviews & Verifies Submitted Docs  │
 └─────────┬───────────────────────────────────┘
           ↓
  ┌─────────────────────────────┐
  │ Dashboard Tracks Progress   │
  │ (Visual + Status Alerts)    │
  └─────────┬───────────────────┘
            ↓
    ┌────────────────────────┐
    │ Onboarding Completed✅ │
    └────────────────────────┘
