# Milestone 2: Auth & Security (FastAPI)

This folder contains the FastAPI backend for authentication and security.

How to run:
1. Download and extract Milestone2_Code.zip
2. Install requirements: pip install -r requirements.txt
3. Create your .env file with JWT_SECRET and MAIL credentials
4. Run the server: uvicorn main:app --reload

Key Features:
- JWT Authentication and bcrypt password hashing
- M1 Validation rules (Email 2/2/2, strong passwords, confirm match)
- Account lockout after 5 wrong passwords
- Real user_of() token check (replaces localuser.py)
- OTP and security-question password recovery
- Seed script to create the first Admin

Files included:
- main.py (FastAPI app)
- auth.py (Signup, login, reset routes)
- models.py (Database tables)
- schemas.py (M1 validation rules)
- security.py (JWT and bcrypt)
- mailer.py (Email OTP)
- database.py (Database connection)
- seed.py (Admin creation)
