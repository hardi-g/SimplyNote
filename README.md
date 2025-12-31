# SimplyNote
**A Simple Note-Taking Application**

SimplyNote is a lightweight, full-stack note-taking application built to provide a clean and minimal experience for creating and managing notes. The project demonstrates a straightforward yet production-style architecture using modern web technologies.

---

## Features

- Create, Edit, and Delete Notes
- Persistent Storage
  - Notes stored in a local **SQLite** database
- Fast & Minimal UI
  - Clean, distraction-free interface
- Fully Dockerized
  - Frontend and backend run in isolated containers
  - Simple and reproducible setup

---

## Tech Stack
- **React**
  - Component-based UI
  - Responsive and minimal design
- **Django**
  - REST-style API for note management
  - Handles application logic and data persistence
- **SQLite**
  - Lightweight relational database for simplicity and ease of use
- **Docker**
  - Docker Compose for multi-service orchestration
 
---

## Running the Project
- Install Docker and then run:
```bash
git clone https://github.com/imhrdk/SimplyNote.git
cd SimplyNote
docker-compose up --build
```
- Access the project from `127.0.0.1:3000`.

---

## Project Goals
- Build a clean and minimal full-stack application
- Demonstrate Django–React integration
- Use SQLite for lightweight persistence
- Practice containerized development with Docker

---

##Future Enhancements
- User authentication
- Note tagging and search
- Markdown support
- Sync across devices

---

## Screenshots
<img width="1470" height="805" alt="Screenshot 2025-12-26 at 19-32-37 React App" src="https://github.com/user-attachments/assets/95a2a9a3-21b4-4c17-a0e3-5a9990ad3517" />
<img width="1470" height="805" alt="Screenshot 2025-12-26 at 19-33-00 React App" src="https://github.com/user-attachments/assets/58802d13-b648-46a7-8b01-1bc255e319dc" />
