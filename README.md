This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

---

# 📁 Project Management System for Colleges & Mentorship Programs

A role-based project management platform built using **Next.js**, tailored for academic environments and mentorship workflows. Features include dashboards for Admins, Guides, and Students, secure authentication, Google Meet scheduling, and team collaboration.

---

## 🚀 Features

- 🧑‍💼 **Role-based dashboards** (Admin, Guide, Student)
- 🔐 **Secure Auth** using SHA-256 + HTTP-only cookies
- 🧑‍🤝‍🧑 **Team formation** from a public project list
- 📅 **Guides can schedule Google Meet sessions**
- 📊 **Project and progress management**
- 🖥️ **Responsive UI** powered by **TailwindCSS** and **shadcn/ui**

---

## 🛠 Tech Stack

- **Frontend**: React (Next.js), TailwindCSS, shadcn/ui
- **Backend**: Next.js API Routes
- **Auth**: SHA-256 encryption, HTTP-only cookies
- **Database**: MySQL
- **Other**: JWT, Google Meet integration

---

## 🔧 Setup Instructions

```bash
git clone https://github.com/yourusername/project-management-system.git
cd project-management-system
npm install
npm run dev
```

🔑 Configure your `.env.local`:

```env
DB_USER=your_db_user
DB_PASS=your_db_pass
DB_NAME=your_db_name
JWT_SECRET=your_jwt_secret
```

---

## 📂 Project Structure

```
/app
  └── pages/ (role-specific UI & routes)
  └── api/ (auth & data endpoints)
  └── components/ (shared UI components)
  └── lib/ (DB, auth, utilities)
```

---

## 🔐 Security

- **Role-based Access Control (RBAC)**
- **Encrypted Tokens (SHA-256)**
- **Secure Cookie Management**

---

## 👥 User Roles

- **Admin**: Manages users, projects, system settings
- **Guide**: Views teams, schedules meets, monitors progress
- **Student**: Joins teams, submits projects, collaborates

---

## 📸 Screenshots

_Add screenshots of each dashboard here (Admin, Guide, Student)_  
Or embed a project carousel if deployed.

---

## 📌 Use Cases

- College Final Year Projects
- Mentorship-based Programs
- Incubation Labs & Innovation Cells

---
