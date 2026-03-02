# 🦷 Dental DCA Portal Automation — UiPath + Denticon

> UiPath bot fetches customer data from database, logs into 
> Denticon DCA Service Portal, performs human-like actions, 
> downloads invoices and saves them back to database 
> automatically. Built for medical/dental industry.

---

## 🔄 Workflow Overview
```
🗄️ Database
   → Bot Fetches Customer Data
      ↓
🌐 Denticon DCA Portal
   → Bot Logs In (Username & Password)
   → Types Customer Information
   → Clicks, Hovers & Scrolls
   → Navigates to Invoice Section
   → Downloads Invoice PDF
      ↓
🗄️ Back to Database
   → Attaches PDF to Customer File
   → Updates Customer Record
      ↓
✅ Process Complete
```

---

## ⚙️ Features

- 🗄️ **Database Integration** — Reads customer data automatically
- 🔐 **Secure Portal Login** — Credentials via UiPath Orchestrator
- 🖱️ **Full UI Automation** — Types, clicks, hovers & scrolls
- 📄 **Invoice Download** — Downloads PDF from Denticon portal
- 📎 **Database Attachment** — Saves PDF to customer record
- 🔒 **HIPAA Aware** — No real patient data stored in automation
- 🏥 **Medical Grade** — Built specifically for dental industry

---

## 🖥️ Portal Details

| Detail | Info |
|--------|------|
| Portal | Denticon DCA Service Portal |
| Website | denticon.com |
| Industry | Medical / Dental |
| Actions | Login, Search, Click, Hover, Scroll, Download |

---

## 🤖 UI Actions Performed

| Action | Purpose |
|--------|---------|
| ⌨️ Typing | Enter customer details |
| 🖱️ Clicking | Navigate portal buttons |
| 🖱️ Hovering | Trigger dropdown menus |
| 📜 Scrolling | Navigate long pages |
| ⬇️ Downloading | Save invoice PDF |

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| UiPath Studio | Main automation platform |
| UiPath UI Automation | Human-like portal interaction |
| UiPath Database Activities | Customer data extraction |
| UiPath PDF Activities | Invoice handling |
| UiPath Orchestrator | Secure credential storage |
| Denticon DCA Portal | Target automation system |

---

## 🚀 How to Run

1. Open `project.json` in UiPath Studio
2. Configure `Config.xlsx`:
   - Database connection string
   - Portal credentials (via Orchestrator Assets)
   - Download folder path
   - Database attachment settings
3. Run `Main.xaml`

---

## 📁 Project Structure
```
├── Main.xaml
├── project.json
├── Config.xlsx
├── Workflows/
│   ├── GetCustomerFromDB.xaml
│   ├── Portal_Login.xaml
│   ├── Portal_NavigateCustomer.xaml
│   ├── Portal_DownloadInvoice.xaml
│   └── DB_AttachInvoice.xaml
└── README.md
```

---

## 💼 Business Value

| Before Automation | After Automation |
|-------------------|-----------------|
| Staff logs in manually | Bot handles login automatically |
| Manual data entry on portal | Bot types all data instantly |
| Hours downloading invoices | Minutes for full process |
| Manual PDF filing | Auto-attached to customer record |
| Human errors in data entry | 100% accurate every time |

---

## 🔒 Data & Privacy

- No real patient data included in repository
- All credentials stored in UiPath Orchestrator (encrypted)
- Built in compliance with medical data privacy standards
- Database connection strings removed from code

---

## 👨‍💻 About the Developer

**RPA & AI Automation Developer** specializing in UiPath,
medical/dental industry automation & database integration.

📩 **Available for freelance projects!**

---

⭐ If you find this useful, please star the repo!
