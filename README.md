# Mehran Public Higher Secondary School — Advanced ERP

School: **Mehran Public Higher Secondary School, Ranipur / Gambat**

This is an upgrade of the existing EduCloud demo project, not a new project from zero.

## Included in this upgraded prototype
- Sign In + Sign Up + Forgot Password UI
- Role-aware dashboards: Admin, Principal, Teacher, Student, Parent, Exam Department
- Class-wise student lists and Add Student
- Passport photo field for student registration
- Subject-wise teacher lists and multiple teachers per subject
- Teacher → Subject → Class assignment concept
- Class-based attendance flow with automatic student roster
- Results entry and professional printable colored A4 marksheet
- Month-wise student fees and staff dues
- Regular timetable and official Exam Department timetable with print/PDF
- Admissions, staff/job portal, homework, finance, leave, inventory, transport, library, notices, academic year and security sections
- Expanded Supabase schema for the Advanced ERP

## Important
The browser demo uses localStorage so it can be tested without a database. Supabase credentials are intentionally blank in `config.js`. Before production use, configure Supabase Auth, Storage, database migrations, RLS policies, backups and restore testing.

## Deploy
Upload the project files to GitHub and deploy the repository through Cloudflare. Do not expose a Supabase service-role key in browser code.
