# 📚 VerseBooks

**VerseBooks** is a modern and minimalist online bookstore built with Next.js, Tailwind CSS, and Supabase.  
It offers a seamless experience for both readers and administrators, with secure authentication, book catalog browsing, and inventory management. Fully deployed on Vercel.

---

## ✨ Features

- 🛍️ Browse and search books by title, author, or category  
- 🔐 User authentication using Supabase Auth (email login)  
- 🛒 Add to cart & simulate checkout flow  
- 📦 Admin dashboard to manage book inventory  
- 🌙 Clean and modern UI with Tailwind CSS & shadcn/ui  
- ☁️ Deployed on Vercel, backed by Supabase PostgreSQL  

---

## 🧱 Tech Stack

| Technology        | Description                          |
|-------------------|--------------------------------------|
| [Next.js](https://nextjs.org)          | Fullstack React framework with App Router |
| [Tailwind CSS](https://tailwindcss.com) | Utility-first CSS framework                |
| [shadcn/ui](https://ui.shadcn.com/)    | Accessible and stylish UI components       |
| [Supabase](https://supabase.com)       | Auth & PostgreSQL as a Service             |
| [Vercel](https://vercel.com)           | Deployment and hosting                     |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/ZeroTwo71/versebooks.git
cd versebooks
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Setup Environment Variables

Rename `.env.example` to `.env.local` and fill with your Supabase project credentials:

```env
NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-anon-key
```

### 4. Run Development Server

```bash
npm run dev
```

Then open your browser at `http://localhost:3000`

---

## 🗂️ Project Structure

```
/app               → App Router pages and layouts
/components        → Reusable UI components
/lib               → Supabase client & utils
/public            → Static assets (book covers, etc)
/ui                → shadcn/ui components
```

---

## 🔐 Roles & Permissions

| Role   | Access                                   |
|--------|------------------------------------------|
| Admin  | Add/edit/delete books, view orders       |
| User   | Browse catalog, add to cart, checkout    |

Roles are assigned via Supabase `users` table using metadata or RLS policies.

---

## 🧠 Learning Objectives

This project is built to learn:

- 🔗 Supabase integration (Auth + DB)  
- 🧠 Role-based access (admin & user)  
- 🧩 Fullstack app using Next.js App Router  
- ✨ Component styling with Tailwind and shadcn/ui  
- 🚀 Deployment flow with Vercel  

---

## 📦 Deployment Guide

1. Push your code to GitHub  
2. Go to [vercel.com](https://vercel.com) and import the project  
3. Set environment variables (Supabase URL & Key)  
4. Click deploy, done 🎉  

---

## 📄 License

Licensed under the MIT License.  
Feel free to fork, modify, and build your own version! 🚀

---

Made with ❤️ by [ZeroTwo71](https://github.com/ZeroTwo71)
