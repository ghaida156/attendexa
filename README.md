# Attendexa
### A Secure Anonymous Smart Attendance Platform for Universities

Graduation Project | CYBS4491 | University of Hafr Al Batin | April 2026

## Overview
Attendexa is a smart attendance management platform that automates and secures attendance registration through multi-layer verification. Unlike traditional QR-based systems that rely on static codes, Attendexa combines dynamic QR generation, GPS geofencing, university Wi-Fi validation, and device-level authentication to eliminate proxy attendance and reduce fraud.

## Key Features
- 🔄 **Dynamic QR Codes** — Refresh every 10 seconds using TOTP-based generation, preventing screenshot sharing
- 📍 **GPS Geofencing** — Validates student location against classroom boundaries
- 📶 **University Wi-Fi Validation** — Confirms device is connected to institutional network
- 🔐 **JWT Authentication** — Secure, role-based access control for Admins, Instructors, and Students
- 🤖 **AI-Powered Fraud Detection** — Real-time monitoring and anomaly alerts
- 📊 **Analytics & Reporting** — Exportable attendance reports (PDF/Excel) with institutional insights
- ⚡ **Real-Time Sync** — Live attendance dashboards updated instantly

## Tech Stack
**Frontend:** React (Vite), TypeScript, Tailwind CSS, Shadcn UI
**Backend:** Node.js, Express.js, RESTful APIs
**Database:** PostgreSQL
**Auth & Security:** JWT, Bcrypt password hashing, AES-256, TLS 1.3

## Results
- ✅ QR validation time: under 0.8 seconds
- ✅ Attendance registration: under 1 second
- ✅ 95% of requests completed in under 3 seconds (100 concurrent users)
- ✅ Passed functional, security, performance, and usability testing

## System Architecture
Three-tier client-server architecture:
1. **Frontend Layer** — React SPA for user interaction
2. **Backend/API Layer** — Business logic, authentication, validation
3. **Database Layer** — PostgreSQL for relational data integrity

## User Roles
- **Administrator** — User/room management, institutional analytics, fraud monitoring
- **Instructor** — Session creation, QR generation, live attendance tracking, exports
- **Student** — QR scanning, attendance history, schedule viewing

## Documents
- 📄 [Final Report](./FINAL_REPORT_-_Template__2_.pdf)
- 📊 [Final Presentation](./Final_Proj_Presentaion__1___1_.pdf)
- 💻 Source Code: `attendexa.zip`

## Team
| Name | Role |
|------|------|
| Ghaida Bandar Aldossary | Project Manager, Development Engineer |
| Reem Mohammed Aba Alkhayl | System Architect, Test Engineer |
| Almas Racheed Alanazi | Requirements Analyst, Systems Designer |

**Advisor:** Dr. Mazyounah Alfughom

## Future Enhancements
- Facial recognition integration
- Native mobile app (iOS/Android)
- Predictive analytics & risk forecasting
- Cloud deployment
- LMS integration (Moodle, Blackboard)
