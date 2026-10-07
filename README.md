# SERS - Student Elective Registration System
### Team NOVA | Group 14 | Mahindra University | April 2026

## Team

| Name | Roll Number |
|------|-------------|
| H. Aakanksh Reddy | SE23UARI048 |
| Ananya Agrawal | SE23UARI010 |
| Aishika Reddy | SE23UARI075 |
| Shruti Verma | SE23UARI116 |
| N. Sudhiksha | SE23UCSE119 |
| P. Sishir K. Reddy | SE23UCSE136 |
| S. Nayanasakhi | SE23UMCS056 |

---

## Live Deployment

| Component | URL |
|-----------|-----|
| Website Link | https://sers-frontend-de9z.vercel.app |

---

## Test Login Credentials

| Role | Username | Password |
|------|----------|----------|
| Student | SE23UARI048 | password |
| Admin | adminravi@sers.com | password |
| Professor | profsharma@sers.com | password |

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React 18, Axios, React Router, Recharts |
| Backend | Java 17, Spring Boot, Spring Security, Hibernate JPA |
| Database | PostgreSQL 17 on Supabase |
| Deployment | Vercel (frontend), Railway (backend) |

---

## Features

### Student
- Role-based login (Student / Admin / Professor)
- Weekly timetable with fixed courses pre-loaded
- Browse CORE and HUMANITIES electives
- Preview electives on timetable before confirming
- Automatic clash detection
- Seat availability tracking
- Category limit enforcement
- Export timetable as PNG
- Light/Dark mode toggle

### Admin
- Dashboard with enrollment statistics and seat fill rate chart
- Full course management (Create, Read, Update, Delete)
- View all students and enrollments
- Manual allocation override

### Professor
- View assigned courses and enrolled students

---

## Project Documents

All documents are in the `/docs` folder:
- Problem Statement
- SRS (Software Requirements Specification)
- SDS (Software Design Specification)
- Test Plan

---

## Notes

- Database may take 30 seconds to wake up if inactive
- All 50 student records, 18 courses, 14 faculty are pre-seeded
