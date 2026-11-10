# CarePoint — Hospital Management Dashboard

**Created by Zuha Irfan** · Front-end internship project · React + Vite

CarePoint is a responsive, front-end-only hospital dashboard prototype. It uses fictional demo data and browser `localStorage`; it does not connect to a backend or store real medical records.

## Features
- Mock role-based login (Admin, Doctor, Receptionist)
- Dashboard metrics, monthly activity chart and appointment overview
- Patient search, status filtering, add/edit/delete and detail view
- Doctor directory with specialty and availability filters
- Appointment booking, rescheduling, cancellation and status updates
- Invoice creation, paid/unpaid status, printable invoice and CSV export
- Dark mode, responsive sidebar and toast feedback
- Data persists in this browser using localStorage

## Run locally
1. Install Node.js (18 or newer).
2. Extract the ZIP and open this folder in VS Code.
3. Open Terminal → New Terminal.
4. Run:
   ```bash
   npm install
   npm run dev
   ```
5. Open the local URL printed by Vite (usually http://localhost:5173).

## Build
```bash
npm run build
npm run preview
```

## Deploy to Vercel
1. Push this folder to a GitHub repository.
2. In Vercel choose **Add New → Project** and import the repository.
3. Framework preset: **Vite**. Build command: `npm run build`. Output directory: `dist`.
4. Deploy. No environment variables are required.

## Demo login
Choose any role and use any name/email. The login is simulated and does not authenticate against a server.

## Project structure
```
src/
  components/  reusable UI components
  data/        fictional starter data
  App.jsx      application state and page composition
  main.jsx     React entry point
  styles.css   responsive design system
```

## Safety note
All patient and billing records are fictional sample data. Do not add real patient information, passwords, or medical records. This project is a UI prototype only; it is not suitable for clinical use.

## Suggested next improvements
- Add automated tests with Vitest and React Testing Library
- Add server-side authentication and role permissions
- Connect a secure API and database with audit logging
- Add calendar drag-and-drop and PDF invoice export
