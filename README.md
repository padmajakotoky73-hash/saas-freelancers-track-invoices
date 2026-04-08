```markdown
# Freelancer Invoice Tracker

![License](https://img.shields.io/badge/license-MIT-blue)
![Next.js](https://img.shields.io/badge/Next.js-13-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-0.95-green)

A SaaS platform for freelancers to track and manage invoices effortlessly.

## Features

- Create, edit, and send invoices
- Track payment status (paid/unpaid)
- Client management
- Dashboard with financial overview
- Secure authentication

## Quick Start

1. Clone the repo:
   ```bash
   git clone https://github.com/your-repo/saas-freelancers-track-invoices.git
   cd saas-freelancers-track-invoices
   ```

2. Install dependencies:
   ```bash
   # Frontend
   cd frontend && npm install
   
   # Backend
   cd ../backend && pip install -r requirements.txt
   ```

## Environment Setup

Create `.env` files in both `frontend` and `backend` directories:

**Frontend (Next.js):**
```env
NEXT_PUBLIC_API_URL=http://localhost:8000
```

**Backend (FastAPI):**
```env
DATABASE_URL=sqlite:///./invoice.db
SECRET_KEY=your-secret-key
```

## Deployment

1. **Backend**:
   ```bash
   cd backend
   uvicorn main:app --reload
   ```

2. **Frontend**:
   ```bash
   cd frontend
   npm run dev
   ```

Access the app at `http://localhost:3000`

## License

MIT License - see [LICENSE](LICENSE) for details.
```