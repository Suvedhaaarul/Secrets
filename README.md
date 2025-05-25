# 🔐 Secrets Authentication Project

A full-stack authentication-based web application built to practice **user registration, login, password hashing**, **OAuth (Google)**, and **session management**. Once authenticated, users can view secrets and post their own — stored securely in a PostgreSQL database.

---

## 🧰 Tech Stack

- **Frontend:** HTML, CSS, JavaScript, EJS
- **Backend:** Node.js, Express.js
- **Database:** PostgreSQL
- **Authentication:** Passport.js with Local Strategy & Google OAuth 2.0

---

## 📦 Packages Used

- `express` – Web framework
- `bcrypt` – Password hashing and salting
- `passport` – Authentication middleware
- `passport-local` – Local strategy for login/signup
- `passport-google-oauth20` – Google OAuth strategy
- `express-session` – Persistent login sessions
- `connect-pg-simple` – PostgreSQL session store
- `dotenv` – Environment variables
- `pg` – PostgreSQL client for Node.js
- `ejs` – Server-side rendering

---

## 🚀 Features

- User **registration with password hashing + salting** (using bcrypt)
- **Login with email + password** or **Google OAuth**
- **Session persistence** using express-session
- **Secrets page** shown only after authentication
- Authenticated users can **submit secrets**
- PostgreSQL used to **store user data & secrets**

---
🛠️ How to Run Locally

Install dependencies:
npm install

Set up your .env file.

Set up your PostgreSQL table.

Run the app:
node index.js

Open in browser:
http://localhost:3000

---
🧠 Learning Highlights
User auth with email/password and Google OAuth 2.0

Salting + hashing passwords using bcrypt

Express sessions for login persistence

Conditionally rendering views using EJS

Using Passport strategies (Local & Google)

Securely storing sensitive info using .env and PostgreSQL

---

✨ Screens
🔐 Login and Register Pages

📄 Secrets Page (Post-authentication)

➕ Submit Secret Page
