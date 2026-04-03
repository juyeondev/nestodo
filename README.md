# 🐾 Nestodo

> A cozy todo app where your character works hard — and finally gets to rest.

## ✨ Concept

A warm, illustrated todo app featuring a character living in a cozy room.  
Add up to 5 tasks for the day, check them off one by one, and watch your character
stretch and head to bed when everything is done. 🌙

The app resets every midnight based on your local time — ready for a new day.

Responsive design: full-screen on mobile, centered widget on desktop.

## 🛠 Tech Stack

- **Frontend**: Next.js, Tailwind CSS, Framer Motion
- **Backend**: FastAPI (Python)
- **Database**: PostgreSQL (Supabase)
- **Deployment**: Vercel (frontend) + Render (backend)

## 🗺 Features

### MVP
- [ ] Todo CRUD (up to 5 tasks)
- [ ] Todo check / complete
- [ ] Auto reset at midnight (based on user's local time)
- [ ] Character animation (working → stretch → go to bed)
- [ ] Responsive layout (mobile full-screen / desktop centered)

### Phase 2
- [ ] Window scene that changes by time of day and weather
- [ ] Calendar view to track completed days

### Phase 3
- [ ] Login / Auth
- [ ] Room growth system (decorations unlock as streak grows)
- [ ] Recurring todos

### Phase 4
- [ ] Ambient sounds (keyboard typing, rain, etc.)

## 📝 Dev Log

See [docs/DEVLOG.md](docs/DEVLOG.md)