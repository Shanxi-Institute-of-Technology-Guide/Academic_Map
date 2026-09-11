# Academic Map

Academic Map is a full-stack academic information application. It contains a Spring Boot backend and a Vue 3 frontend.

> Academic context: this directory contains a course lab or coursework solution.

## Structure

- `Academic_Map/`: Java 21 Spring Boot service
- `frontend/`: Vue 3 and Vite client
- `sql/academic_map.sql`: database initialization script

## Run Locally

Start the backend:

```powershell
cd Academic_Map
.\mvnw.cmd spring-boot:run
```

Start the frontend in another terminal:

```powershell
cd frontend
npm install
npm run dev
```

Use a Java 21 JDK and Node.js 20.19 or newer. Configure the database connection before starting the backend when MySQL is used.