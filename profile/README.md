# 🏨 Akkor Hotels - Hotel Booking System

Welcome to **Akkor Hotels**! This organization is dedicated to building a modern hotel booking system that provides a seamless experience for users and robust management tools for administrators. Our goal is to ensure **scalability, security, and an excellent user experience**.

---

## 📂 Project Repositories

<div align="center">

| Repository                                                          | Description                                                        |
| ------------------------------------------------------------------- | ------------------------------------------------------------------ |
| [Backend](https://github.com/Akkor-Hotel/backend)                  | Manages API services, authentication, and database interactions.   |
| [Frontend](https://github.com/Akkor-Hotel/frontend)                 | The web-based user interface for searching, booking, and managing hotels. |
| [Project Board](https://github.com/orgs/Akkor-Hotel/projects/1/views/1) | Development roadmap and ongoing tasks tracking.                   |

</div>

---

## 📖 Project Overview

Akkor Hotels is a full-stack hotel booking system where users can search for hotels, make bookings, and manage their reservations. Admins have access to hotel and booking management tools.

### 🏗️ Core Features:
- **Hotel Management** (CRUD operations for admins)
- **User Authentication & Role Management** (Admins, Employees, and Customers)
- **Secure Payment Processing** (Stripe or another provider)
- **Booking System** (Search, filter, and manage hotel reservations)
- **Cloud Deployment** (Hosting backend and database in a scalable cloud environment)

---

## 🚀 Technologies Used

| Component      | Technology Stack                                             |
| -------------- | ------------------------------------------------------------ |
| **Backend**    | NestJS, PostgreSQL, Docker, TypeORM, Cloud Deployment       |
| **Frontend**   | Next.js, React, Material-UI, TypeScript                     |
| **Database**   | PostgreSQL (via Docker for local, Cloud DB for production)  |
| **Auth**       | PassportJS, JWT-based authentication                        |
| **CI/CD**      | GitHub Actions, Docker Compose                              |

---

## ✅ Prerequisites

To set up and run the project locally, ensure you have:

1. **Node.js** (>= 16.x) & **npm** (>= 8.x)
2. **Docker** (for PostgreSQL and local development)
3. **NestJS CLI** (for backend development)
4. **Environment Variables**: Configure your `.env` files

---

## 🏃 Running the Project Locally

### Backend Setup

```sh
git clone git@github.com:Akkor-Hotel/backend.git
cd backend
npm install
cp .env.example .env
docker-compose up -d
npm run start:dev
```

Backend API should be available at `http://localhost:3000`

### Frontend Setup

```sh
git clone git@github.com:Akkor-Hotel/frontend.git
cd frontend
npm install
cp .env.example .env.local
npm run dev
```

Frontend should be available at `http://localhost:3000`

---

## 🛠️ Deployment & Production Notes

- **Local Database**: Use `docker-compose` for PostgreSQL.
- **Cloud Database**: Deploy PostgreSQL via AWS RDS, Supabase, or Google Cloud SQL.
- **Environment Secrets**: Store API keys and credentials securely.
- **CI/CD**: Implement GitHub Actions for automated testing and deployment.

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

---

For more information, visit our repositories or contact the development team.

**Happy Coding! 🚀**

