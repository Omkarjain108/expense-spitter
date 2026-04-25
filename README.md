# Expense Splitter

A full-stack web application for managing shared expenses and settlements within groups.

## Features

- **User Authentication**: Signup/signin with OTP verification
- **Group Management**: Create groups, invite members, auto-add feature
- **Expense Tracking**: Add, edit, delete expenses with multiple split methods
- **Settlement Management**: Automatic balance calculation and settlement tracking
- **Real-time Chat**: Group messaging functionality
- **Notifications**: Stay updated on group activities and invitations
- **Dashboard**: View personal statistics and current balances

## Tech Stack

**Frontend**: React, Vite, TailwindCSS, Shadcn UI  
**Backend**: Node.js, Express, MongoDB, Socket.IO  
**Authentication**: JWT  

## Setup

### Backend
```bash
cd backend
npm install
# Configure .env file with MongoDB URI and email credentials
npm run dev
```

### Frontend
```bash
cd frontend
npm install
# Configure .env file with backend API URL
npm run dev
```

## Environment Variables

**Backend (.env)**
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_email
EMAIL_PASS=your_email_password
PORT=5000
```

**Frontend (.env)**
```
VITE_API_URL=http://localhost:5000
```

## Documentation

- [Expense Logic Explained](EXPENSE_LOGIC_EXPLAINED.md)
- [Settlement Math](EXPENSE_SETTLEMENT_MATH.md)
