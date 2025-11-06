

# 📈 Stocker — AI-Powered Stock Market Platform



## ✨ Introduction

**Stocker** is an AI-driven, real-time stock market platform built with **Next.js**, **Better Auth**, **Inngest**, and **Shadcn**.
It allows users to track live stock prices, manage personalized watchlists, set smart alerts, and explore AI-powered insights — all in one unified dashboard.

An **admin panel** enables stock management, news publishing, and analytics tracking, while **Inngest** powers background workflows like automated alerts, earnings digests, and sentiment analysis.
It’s designed for developers and traders who want a fast, intelligent, and event-driven financial web app.

---

## ⚙️ Tech Stack

| Category     | Technology                               | Description                                                     |
| ------------ | ---------------------------------------- | --------------------------------------------------------------- |
| **Frontend** | Next.js, TypeScript, Shadcn, TailwindCSS | Modern React-based UI with type safety and reusable components. |
| **Backend**  | Better Auth, Inngest, Nodemailer         | Authentication, background jobs, and email alerts.              |
| **Database** | MongoDB Atlas                            | NoSQL database for users, alerts, and analytics.                |
| **APIs**     | Finnhub, Gemini AI                       | Market data and AI summaries for insights.                      |

---

## 🔋 Features

* ⚡ **Live Stock Dashboard** – Interactive charts with real-time and historical data.
* 🔍 **Smart Search** – Instantly find stocks by name, symbol, or industry.
* 📊 **Personal Watchlists** – Add, edit, and monitor your favorite stocks.
* 🔔 **Custom Alerts** – Receive instant email notifications for price or volume triggers.
* 🧠 **AI-Generated Insights** – Daily summaries, performance digests, and sentiment analytics powered by Gemini AI.
* 🔄 **Event-Driven Workflows** – Automated tasks handled by Inngest for real-time reliability.
* 💬 **Email Notifications** – Integrated with Nodemailer for transactional updates.
* 🛠️ **Admin Dashboard** – Manage stock data, publish market news, and analyze user engagement.

---

## 🤸 Quick Start

### **Prerequisites**

Ensure you have these installed:

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/en)
* [npm](https://www.npmjs.com/)

---

### **Clone the Repository**

```bash
git clone https://github.com/your-username/stocker.git
cd stocker
```

---

### **Install Dependencies**

```bash
npm install
```

---

### **Set Up Environment Variables**

Create a `.env` file in the project root and add the following:

```env
NODE_ENV='development'
NEXT_PUBLIC_BASE_URL=http://localhost:3000

# FINNHUB
NEXT_PUBLIC_FINNHUB_API_KEY=
FINNHUB_BASE_URL=https://finnhub.io/api/v1

# MONGODB
MONGODB_URI=

# BETTER AUTH
BETTER_AUTH_SECRET=
BETTER_AUTH_URL=http://localhost:3000

# GEMINI
GEMINI_API_KEY=

# NODEMAILER
NODEMAILER_EMAIL=
NODEMAILER_PASSWORD=
```

Get your credentials from:

* [Finnhub](https://finnhub.io) — Real-time market data
* [MongoDB Atlas](https://www.mongodb.com) — Database
* [Gemini AI](https://aistudio.google.com/) — AI summarization
* [Inngest](https://www.inngest.com) — Event workflows

---

### **Run the Application**

```bash
npm run dev
npx inngest-cli@latest dev
```

Then open [http://localhost:3000](http://localhost:3000) in your browser 🚀

---

## 🔗 Assets

All assets and visuals used in this project are available in the `/public/readme` folder.

---

## 🚀 Future Enhancements

* 📱 Mobile-optimized dashboard with PWA support
* 🪙 Cryptocurrency integration
* 📈 Portfolio tracker with ROI & risk analytics
* 🤖 Advanced AI-based stock recommendations

---

## 🧑‍💻 About

**Stocker** is a personal full-stack project showcasing advanced event-driven architecture, secure authentication, and AI integration in modern financial web apps.
Built with scalability, modularity, and developer experience at its core.


