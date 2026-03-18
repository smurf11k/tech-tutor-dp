# TechTutor

> Modern LMS platform for creating, selling, and consuming online courses.

---

## Overview

**TechTutor** is a full-stack learning platform built with a scalable architecture.  
It supports course management, payments, quizzes, and progress tracking.

---

## Tech Stack

| Layer    | Technology        |
| -------- | ----------------- |
| Backend  | Laravel (PHP)     |
| Frontend | React (SPA + SSR) |
| Database | PostgreSQL        |
| Search   | MeiliSearch       |
| API      | REST              |

---

## Features

### Students

- Sign up / Login (Email + OAuth)
- Purchase courses
- Watch lessons (video, text, files)
- Pass quizzes & get results
- Track learning progress
- Leave reviews & comments

---

### Instructors/Teachers

- Create & manage courses
- Upload lessons & materials
- Build quizzes
- Track student progress
- View course analytics

---

### Admin

- Manage users & roles
- Moderate content
- Monitor platform activity
- Manage payments

---

## Authentication & Security

- JWT / Session-based auth
- Email verification
- Password reset
- Optional 2FA
- Rate limiting & CAPTCHA
- Protection against XSS / SQL Injection

---

## Core Capabilities

- Course search & filtering
- Responsive UI
- Notifications (Email / Push)
- Payment integration (LiqPay / Stripe)
- Analytics integration

---

## Data Model

```
User
Course
Module
Lesson
Quiz
QuizAttempt
Enrollment
Progress
```

---

## API

RESTful API for all core features.

---

## Architecture Notes

- Role-based access control (RBAC)
- SSR for performance & SEO
- Modular structure (Courses → Modules → Lessons)
- Scalable service integrations

---

## Roadmap

- [ ] Multi-language support

## Additional

[Design Template](https://dp-tech-tutor-template.netlify.app/)
