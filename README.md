# oloid-pulse
A side project to practice and develop fundementals 

# Oloid Pulse

**Oloid Pulse** is an internal web application designed to help Oloid employees easily discover and connect with colleagues and customers.

This tool serves as a lightweight **Employee & Customer Directory**, enabling improved collaboration, onboarding, and visibility across distributed teams.

---

## 🚀 Features (MVP)

### 👥 Employee Directory
- Search employees by name, team, or location
- View profile cards with:
  - Name, role, email, phone
  - Birthday and work anniversary
  - Slack DM link (optional)

### 💼 Customer Directory
- View a list of customers segmented by stage: Prospect, New, or Existing
- Show account owner and recent activity summary

### 🔔 Slack Notifications (Stretch Goal)
- Daily Slack message to a selected channel for birthdays and anniversaries
- Configurable via environment variables or admin panel

### 🔐 Authentication
- Login using Google (OIDC)
- Secure route access for internal users only

---

## 📚 Tech Stack & Learning Goals

| Layer         | Stack / Tools                | Learning Focus                     |
|---------------|------------------------------|------------------------------------|
| Frontend      | HTML, CSS, JavaScript        | JS Basics, DOM, Fetch API          |
| Backend (opt) | Node.js or Python Flask      | REST API, Express/Flask setup      |
| Data Layer    | JSON / CSV / APIs (GSuite, Salesforce) | REST/SOAP, XML parsing     |
| Auth          | Google OAuth 2.0 (OIDC)      | OIDC login integration             |
| Notifications | Slack API                    | Bot/Webhook basics                 |
| Docs & Mgmt   | Confluence, Jira              | Agile documentation & tracking     |

---

## 🗂️ Folder Structure (Planned)

oloid-pulse/
│
├── frontend/ # Static frontend (HTML, JS)
├── backend/ # API integration layer (optional)
├── data/ # Sample JSON/CSV datasets
├── docs/ # Architecture diagrams, documentation
└── README.md


---

## ✅ Status

> Project approved for 10% discretionary time by Shankar and Lakshmi.  
> Kickoff: [Insert Date]  
> Repo Created: ✅  
> MVP Planning: In Progress

---

## 📍 Next Steps

- [ ] Add mock employee data in JSON
- [ ] Build basic HTML layout for employee directory
- [ ] Add search/filter functions
- [ ] Explore Google OIDC login

---

## 💬 Contributors

- [Amit Pathak](mailto:amit.pathak@oloid.com) – Project Lead

---

## 📝 Disclaimer

Oloid Pulse is an internal tool created as part of a learning initiative and is not intended for public release or commercial use. All data is either mock or limited to non-sensitive internal usage.
