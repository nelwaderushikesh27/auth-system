# 🔐 Auth System

A production-ready authentication system with JWT & OAuth 2.0.

## ✨ Features
- Email/Password authentication
- Google OAuth 2.0
- GitHub OAuth
- JWT access & refresh tokens
- Role-based access control (RBAC)
- Email verification
- Password reset
- 2FA support
- Rate limiting

## 🛠️ Tech Stack
| Component | Technology |
|-----------|------------|
| **Backend** | Node.js + Express |
| **Database** | MongoDB + Redis |
| **Auth** | Passport.js, JWT |
| **Validation** | Joi |
| **API** | REST + GraphQL |

## 🚀 Quick Start
```bash
git clone https://github.com/nelwaderushikesh27/auth-system.git
cd auth-system
npm install
cp .env.example .env
npm run dev
```

## 📡 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/auth/register | Register |
| POST | /api/auth/login | Login |
| POST | /api/auth/refresh | Refresh token |
| POST | /api/auth/logout | Logout |
| GET | /api/auth/me | Get profile |
| POST | /api/auth/forgot-password | Reset password |
| GET | /api/auth/verify-email/:token | Verify email |

## 📂 Structure
```
auth-system/
├── src/
│   ├── config/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── services/
│   └── utils/
├── tests/
└── README.md
```

---
*Secure by default 🔒*
