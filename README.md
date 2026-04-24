# 🚀 CareerForge AI  
**Your intelligent career advancement assistant powered by AI.**  
Optimize your job search, craft perfect resumes, and navigate your career with confidence.

🌐 **Live Website:** [https://careercraftai.vercel.app](https://carrer-craft-ai.vercel.app/)

---

## ✨ Features

- 🎯 **AI Resume Builder**  
  Professionally formatted, industry-tailored resumes with a single click.

- 📝 **Cover Letter Generator**  
  Personalized cover letters aligned with your job applications.

- 💡 **Technical Interview Prep**  
  Practice real-world questions and get intelligent feedback.

- 📊 **Industry Insights Dashboard**  
  Data-driven career guidance tailored to your field.

---

## 🧱 Tech Stack

| Layer            | Technologies Used                                  |
|------------------|----------------------------------------------------|
| **Frontend**     | Next.js 13+ (App Router), React, Tailwind CSS, shadcn/ui |
| **Backend**      | Next.js Server Components & API Routes             |
| **Database**     | PostgreSQL (Neon DB)                               |
| **AI Integration**| Google Gemini 1.5 Flash                           |
| **Auth**         | Clerk                                              |
| **State Mgmt**   | React Context API                                  |
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
git clone https://github.com/yourusername/ai-career-coach.git
cd ai-career-coach

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

Run the database migrations and start the dev server:

```bash
npx prisma migrate dev
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

---

## 🙌 Acknowledgements

- [Next.js](https://nextjs.org)  
- [Tailwind CSS](https://tailwindcss.com)  
- [shadcn/ui](https://ui.shadcn.com)  
- [Clerk](https://clerk.dev)  
- [Google Gemini](https://deepmind.google)  
- [Neon DB](https://neon.tech)  
- [Vercel](https://vercel.com)  

---

Made with ❤️ by Gupta_Nawneet
