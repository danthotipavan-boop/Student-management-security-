# Secure FSD Application

Starter full-stack application demonstrating layered security with:
- React frontend
- Node.js + Express backend
- MongoDB + Mongoose
- bcrypt password hashing
- JWT in an HttpOnly cookie
- Helmet security headers
- CORS configuration
- Rate limiting
- Backend validation
- Role-based authorization
- Environment-based secrets

## Run

### Backend
```bash
cd backend
npm install
cp .env.example .env
# edit .env
npm run dev
```

### Frontend
```bash
cd frontend
npm install
npm run dev
```

The default frontend is http://localhost:5173 and backend is http://localhost:5000.

For production, use HTTPS, a strong random JWT secret, a protected MongoDB deployment, and appropriate CSRF/CSP configuration.
