# Fight Log

**Fight Log** is an API designed for martial arts practitioners to take notes, track training sessions, and organize techniques and strategies in a simple and intuitive way. It is perfect for fighters, coaches, and enthusiasts who want to keep their progress structured and accessible.

---

## Features

### User Management
- Register new users
- Login with JWT authentication
- View user profile

### Training Notes
- Create, read, update, and delete notes
- Organize notes by category or martial art style
- Link notes to specific training sessions

### Workouts (Training Sessions)
- Create, read, update, and delete workouts
- Track date, duration, type, intensity, and drills
- Store additional notes and drills in structured format

---

## Tech Stack
- **Backend:** NestJS
- **Database:** PostgreSQL (or SQLite for testing)
- **ORM:** Prisma or TypeORM
- **Authentication:** JWT
- **Documentation:** Swagger
- **Testing:** Jest
- **Optional:** Docker for database and development environment

---

## Getting Started

### Prerequisites
- Node.js (LTS recommended)
- npm or yarn
- PostgreSQL
- Git

### Installation
1. Clone the repository:

```bash
git clone https://github.com/yourusername/fight-log.git
cd fight-log
