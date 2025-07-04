# 📘 Quick Learn LMS

A modern and scalable **Learning Management System (LMS)** built with the latest web technologies for educators and learners. This project supports content management, secure authentication, and seamless payment processing.

---

## 🚀 Tech Stack

- **Next.js** – Frontend and backend (API routes)
- **TypeScript** – Type-safe development
- **Sanity.io** – Headless CMS for course content
- **Stripe** – Payment integration
- **Clerk** – User authentication and management
- **Tailwind CSS** – Utility-first styling
- **Admin Dashboard** – Manage users, content, and payments

---

## 🔗 Local Development URLs

- **LMS Frontend**: [http://localhost:3000](http://localhost:3000)  
- **Sanity Studio**: [http://localhost:3333](http://localhost:3333) or [http://localhost:3000/studio](http://localhost:3000/studio)

---

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your-clerk-pk
CLERK_SECRET_KEY=your-clerk-sk

# Stripe
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your-stripe-pk
STRIPE_SECRET_KEY=your-stripe-sk
STRIPE_WEBHOOK_SECRET=your-webhook-secret

# Sanity
NEXT_PUBLIC_SANITY_PROJECT_ID=your-sanity-project-id
NEXT_PUBLIC_SANITY_DATASET=production
# App
NEXT_PUBLIC_BASE_URL=http://localhost:3000