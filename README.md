# 🚀 CareerForge AI  
**Your intelligent career advancement assistant powered by AI.**  
Optimize your job search, craft perfect resumes, and navigate your career with confidence.

🌐 **Live Website:** [https://careercraftai.vercel.app](https://carrer-craft-ai.vercel.app/)

---

## ✨ Features

- 🎯 **AI Resume Builder**  
  Professionally formatted, industry-tailored resumes with a single click.

- 📝 **Cover Letter Generator**  
  Generate tailored cover letters for specific job descriptions.

- 💡 **Technical Interview Prep**  
  Practice with custom-generated interview questions and receive instant AI feedback on your responses.

- 📊 **Industry Insights Dashboard**  
  Data-driven career guidance tailored to your field.

---

## 🧱 Tech Stack

| Layer            | Technologies Used                                  |
|------------------|----------------------------------------------------|
| **Frontend**     | Next.js 15+ (App Router), React, Tailwind CSS, shadcn/ui |
| **Backend**      | Next.js Server Components & API Routes             |
| **Database**     | PostgreSQL (Neon DB)                               |
| **AI Integration**| Google Gemini 3 Flash                           |
| **Auth**         | Clerk                                              |
| **Deployment**   | Vercel                                             |
| **Background Jobs** | Inngest                                        |

---

## 🚀 Getting Started

### ✅ Prerequisites

- Node.js 18+ and npm
- PostgreSQL or Neon DB account
- Google Gemini API Key
- Clerk account

---

### 📦 Installation

```bash
git clone https://github.com/YOUR_USERNAME/CareerForge-AI.git
cd CareerForge-AI
npm install
```

Create a `.env` file and add the following:

```env
DATABASE_URL="your_database_url"
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="your_clerk_publishable_key"
CLERK_SECRET_KEY="your_clerk_secret_key"
NEXT_PUBLIC_CLERK_SIGN_IN_URL="/sign-in"
NEXT_PUBLIC_CLERK_SIGN_UP_URL="/sign-up"
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL="/onboarding"
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL="/onboarding"
GEMINI_API_KEY="your_gemini_api_key"
```

Database Sync and start the dev server:

```bash
npx prisma generate
npx prisma db push
npm run dev
```

---

## 🧩 Architecture

Follows modern Next.js 13+ standards:

```
├── actions/           # Server actions for data mutations
├── app/               # App Router structure
│   ├── (auth)/        # Auth routes
│   ├── (main)/        # Main app routes
│   └── api/           # API endpoints
├── components/        # Reusable UI components
├── lib/               # Shared utilities
│   ├── inngest/       # Background job logic
│   └── prisma/        # Prisma DB client
├── prisma/            # Schema & migrations
└── public/            # Static files
```

---

## 🤝 Contributing

We welcome contributions! Please fork the repo and submit a pull request.

---

## 📄 License

Licensed under the [MIT License](LICENSE).



Made with 💗 by Krishna

B.Tech (IT) Student at BIT Sindri
