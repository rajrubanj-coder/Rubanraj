# Enterprise Timesheet Management System

A comprehensive timesheet management application built with Next.js 15, TypeScript, Tailwind CSS, MySQL, Prisma ORM, NextAuth Authentication, and OpenAI API integration.

## Features

- **Authentication Module**: User registration, login, JWT sessions, password hashing
- **Role-Based Access Control**: Admin, Manager, Employee roles
- **Employee Management**: Add, edit, delete, search employees
- **Timesheet Management**: Daily, weekly, monthly entries with overtime calculation
- **Leave Management**: Apply, approve, reject leaves with balance tracking
- **Projects Module**: Create projects, assign employees, track progress
- **Reports Module**: Employee, timesheet, leave reports with export functionality
- **AI Features**: OpenAI integration for insights and analysis
- **Dashboard**: Modern UI with KPI cards and charts using Recharts
- **Security**: SQL injection protection, XSS prevention, CSRF protection

## Tech Stack

- **Frontend**: Next.js 15, React 19, TypeScript, Tailwind CSS
- **Backend**: Next.js API Routes, Node.js
- **Database**: MySQL with Prisma ORM
- **Authentication**: NextAuth.js
- **Validation**: Zod
- **UI Components**: Shadcn/ui, Recharts
- **AI**: OpenAI API
- **Export**: xlsx, csv, pdf

## Project Structure

```
src/
├── app/
│   ├── api/
│   ├── auth/
│   ├── dashboard/
│   ├── employees/
│   ├── timesheets/
│   ├── leaves/
│   ├── projects/
│   └── reports/
├── components/
│   ├── layout/
│   ├── dashboard/
│   └── ui/
├── lib/
│   ├── auth.ts
│   ├── db.ts
│   └── utils.ts
├── prisma/
│   └── schema.prisma
├── hooks/
├── services/
├── types/
├── utils/
└── middleware/
```

## Getting Started

See SETUP.md for complete setup instructions.

## License

MIT
