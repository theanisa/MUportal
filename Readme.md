**MUportal**
 centralized web platform for **notices and bus schedules** at Metropolitan University, built with the MERN stack.

> **Status:** 🚧 In development (final year project)

---

## The Problem

At our university, notices and bus schedules are both posted in a single WhatsApp channel. Important updates get buried, bus schedules arrive as images that are hard to find later, and nothing can be searched or filtered.

## The Solution

One simple, mobile-friendly website where:

- **Admins** post notices and update the bus timetable in one place
- **Students** see everything instantly, with no login needed

---

## Features

### For Students (no login required)
- View notices, newest first, with important ones pinned
- Search and filter notices by category
- View bus schedules by route and direction
- Notification bell showing recent notice alerts with an unread count
- Fully responsive, mobile-first design

### For Admins (secure login)
- Create, edit, and delete notices
- Pin and unpin important notices
- Add and edit bus routes and timetables
- Post short alert banners (e.g. delays)

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React |
| Backend | Node.js, Express.js |
| Database | MongoDB (Atlas) |
| Authentication | JWT (admin only) |
| Deployment | Vercel / Render |

---

## Project Structure

```
mu-notice-bus-hub/
├── client/          # React frontend
├── server/          # Express backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── middleware/
└── README.md
```

---

## Getting Started

### Prerequisites
- Node.js (v18 or later)
- A MongoDB Atlas account (or local MongoDB)


## Roadmap

- [ ] Database design and backend API
- [ ] Notices (CRUD, categories, search, pinning)
- [ ] Bus schedule management
- [ ] Admin authentication and dashboard
- [ ] Notification bell with unread count
- [ ] Testing and deployment

### Future Scope
- Live bus tracking
- Push notifications
- Mobile app

---

## Design Goals

- **Simple:** only admins log in; no student accounts or file uploads
- **Reliable:** validation on both frontend and backend
- **Low-maintenance:** managed hosting with no server to maintain

---

## Author

**Anisa_Binte_Faruk**
CSE Student, Metropolitan University

## License

This project is developed as an academic final year project.