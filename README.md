# FinMan - AI-Powered Finance Management Platform

FinMan is a modern, full-stack expense tracking and budgeting platform that helps users efficiently manage their personal finances. It provides clean visualizations, intelligent categorization, multi-account support, and receipt scanning — all built with cutting-edge web technologies.

---


---

## 📌 Key Features

- 🔐 **Secure Authentication** using Clerk
- 💰 **Add, Edit, Delete Transactions**
- 🧾 **Receipt Scanner** with OCR (for PDFs/images)
- 📊 **Real-Time Dashboards** using Recharts
- 🔁 **Recurring Transaction Support**
- 🗂️ **Smart Categorization** (Rules-based)
- 🌐 **Multi-Account & Multi-Currency Support**
- 📨 **Email Notifications** with Resend
- 📅 **Date-Filtered Reports** and net income/expense breakdown

---

## 🧱 Tech Stack

### Frontend:
- **Next.js 15** (App Router)
- **React 19**
- **Tailwind CSS + Shadcn UI**
- **Recharts** for data visualization
- **Lucide-react** for icons

### Backend:
- **Next.js API Routes**
- **Prisma ORM**
- **PostgreSQL** database
- **Clerk Authentication**
- **Inngest** for background jobs

### Utilities:
- `zod` (Schema validation)
- `react-hook-form` (Form handling)
- `date-fns` (Date utilities)
- `sonner` (Toast notifications)

---

## 🧠 System Architecture Overview

```
+----------------------+       +---------------------+
|   User Interface     | <-->  |    Clerk Auth       |
|  (Next.js Web App)   |       +---------------------+
+----------+-----------+
           |
           v
+------------------------+
|  API Gateway (Next.js) |
+------------------------+
           |
           v
+------------------------------------------------+
|   Business Logic Layer                         |
|  (Budget Engine, Transaction Parser, OCR)      |
+------------------+-----------------------------+
                   |
                   v
         +-----------------------------+
         | Database (Prisma + SQL)     |
         +-----------------------------+
                   |
                   v
         +-----------------------------+
         | Dashboards & Reports        |
         +-----------------------------+
                   |
                   v
         +-----------------------------+
         | Notifications (Resend, etc.)|
         +-----------------------------+
```

---

## 📷 Screenshots
> Add screenshots here of:
> - Dashboard UI
> - Add Transaction Form
> - Receipt Scanner
> - Reports Page

---

## 🛠️ Installation (Local Development)

```bash
git clone https://github.com/your-username/finman.git
cd finman
pnpm install
pnpm dev
```

> ⚠️ Ensure you configure your `.env` file with:
- Clerk API keys
- PostgreSQL DB URL
- Resend API key (optional)

---

## 🧪 Testing
> To be added in future versions

---

## 📄 License
MIT License © 2025 [Your Name]

---

## 🤝 Let's Connect
- [LinkedIn](https://linkedin.com/in/your-profile)
- [GitHub](https://github.com/your-username)

---

**Built with ❤️ for developers and finance nerds.**

