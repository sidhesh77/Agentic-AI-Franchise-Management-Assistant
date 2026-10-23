# Agentic-AI-Franchise-Management-Assistant

# Milestone 1: User Authentication Module


## 📌 Overview

A secure user authentication web application built with Python and Streamlit. It allows users to register, log in, reset forgotten passwords, and access a personalized dashboard. It also provides a separate admin dashboard to view registered users.

## ✨ Features

- **User Registration:** Create an account with username, email, password, and a security question.
- **Secure Login:** Validate user credentials and create JWT-based sessions.
- **Password Validation:** Check password strength and confirm password matching.
- **Forgot Password:** Reset passwords using a security question or email OTP.
- **Email OTP:** Send a one-time verification code through Gmail.
- **User Dashboard:** Display user information with a logout option.
- **Admin Dashboard:** View registered usernames and email addresses without exposing passwords.
- **Input Validation:** Validate required fields and prevent duplicate usernames.

## 🛠️ Tech Stack

- **Language:** Python
- **Frontend:** Streamlit
- **Database:** SQLite
- **Authentication:** JSON Web Tokens (JWT)
- **Email Service:** Gmail SMTP
- **Environment:** Google Colab and ngrok

## ⚙️ How It Works

1. Users register with their details and create a password.
2. Login verifies the credentials and establishes an authenticated session.
3. JWT is used to manage authentication.
4. Users who forget their password can verify their identity using a security question or email OTP.
5. Authenticated users access their dashboard, while the admin can view registered user details.

## 🚀 How to Run

1. Open `User_Authentication.ipynb` in Google Colab.
2. Configure the required secrets in Colab Secrets:
   - `JWT_SECRET`
   - `NGROK_AUTHTOKEN`
   - `EMAIL_ID`
   - `EMAIL_PASSWORD`
3. Run the notebook cells in order.
4. Open the generated ngrok URL to access the application.

**Note:** Use a Gmail App Password for SMTP. Never upload real credentials, tokens, or passwords to GitHub.

## 📂 Project Structure

```text
Milestone1/
├── README.md
├── User_Authentication.ipynb
└── screenshots/
    ├── login.png
    ├── signup.png
    ├── forgot-security.png
    ├── forgot-otp.png
    ├── otp-email.png
    ├── user-dashboard.png
    └── admin-dashboard.png
```



## 🎯 Outcome

This milestone demonstrates user registration, authentication, password recovery, session management, database integration, and a separate admin interface in a Streamlit application.
