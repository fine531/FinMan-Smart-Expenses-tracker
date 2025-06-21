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
> - (![image](https://github.com/user-attachments/assets/8cb44f3e-33c3-4706-9f60-21e0e57f97f3)![image](https://github.com/user-attachments/assets/7036aab7-9e26-4eb6-8ac1-f609bc6c5513)
> - Add Transaction Form
> - ![image](https://github.com/user-attachments/assets/4e0aa894-5de6-44b1-855c-c9062b598569)
> - Receipt Scanner
> - ![image](https://github.com/user-attachments/assets/9b87c1e3-8d69-4b78-b6e6-eba6c322dd37)

---

## 🛠️ Installation (Local Development)

```bash
git clone https://github.com/fine531/FinMan-Smart-Expenses-tracker.git
cd finman
pnpm install
pnpm dev
```

> ⚠️ Ensure you configure your `.env` file with:
- Clerk API keys
- PostgreSQL DB URL
- Resend API key (optional)

---


## 📄 License
MIT License © 2025 [Dharmavarapu Phanindra]

---

## 🤝 Let's Connect
- [LinkedIn](www.linkedin.com/in/phanindra-dharmavarapu-183093250)
- [GitHub]((https://github.com/fine531/))

---

**Built with ❤️ for developers and finance nerds.**

