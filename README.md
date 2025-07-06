# 🎼 Orkestria

> A comprehensive project management platform designed to orchestrate tasks, resources, and teams with precision and elegance.

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Docker](https://img.shields.io/badge/docker-enabled-blue.svg)](docker-compose.yml)
[![Java](https://img.shields.io/badge/java-21%2B-orange.svg)](https://openjdk.org/projects/jdk/17/)
[![TypeScript](https://img.shields.io/badge/typescript-5.0%2B-blue.svg)](https://www.typescriptlang.org/)

## 🚀 Overview

Orkestria is a modern project management solution that brings together task management, resource allocation, and team coordination in a unified platform. 
It offers scalability, maintainability, and a seamless user experience.

## 🏗️ Architecture

The platform consists of two main components:

- **Backend**: Java Spring Boot application providing RESTful APIs
- **Frontend**: TypeScript/Deno-based web application with Fresh framework

## 🛠️ Tech Stack

### Backend
- **Framework**: Spring Boot
- **Language**: Java 21
- **Database**: PostgreSQL
- **Documentation**: OpenAPI/Swagger
- **Containerization**: Docker

### Frontend
- **Runtime**: Deno
- **Framework**: Fresh
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: Custom component library

## 📦 Features

- 📋 **Task Management**: Create, assign, and track tasks with Kanban boards
- 📅 **Calendar**: Schedule and visualize project 
- 🔄 **Resource Management**: Allocate and monitor project resources
- 👥 **Team Collaboration**: Manage projects and team members
- 🔔 **Notifications**: Stay updated with deadlines

## 🚀 Quick Start

### Prerequisites

- Docker and Docker Compose
- Java 21 (for backend development)
- Deno (for frontend development)

### Running with Docker

```bash
# Clone the repository
git clone https://github.com/Jaime-GC/orkestria.git
cd orkestria

# Start the application
docker-compose up -d
```

The application will be available at:
- Frontend: `http://localhost:8080`
- Backend API: `http://localhost:8080`
- API Documentation: `http://localhost:8080/swagger-ui.html`

### Development Setup

#### Backend
```bash
cd orkestria-backend
./mvnw spring-boot:run
```

#### Frontend
```bash
cd orkestria-frontend
deno task start
```

## 📁 Project Structure

```
orkestria/
├── docker-compose.yml          # Docker orchestration
├── orkestria-backend/          # Java Spring Boot backend
│   ├── src/                    # Source code
│   ├── docs/                   # Architecture diagrams
│   └── dockerfile              # Backend container
├── orkestria-frontend/         # Deno Fresh frontend
│   ├── components/             # Reusable UI components
│   ├── islands/                # Interactive components
│   ├── routes/                 # Application routes
│   └── dockerfile              # Frontend container
└── README.md                   # This file
```



## 📚 API Documentation

The backend provides a comprehensive REST API documented with OpenAPI/Swagger. Access the interactive documentation at:

`http://localhost:8080/swagger-ui.html`

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature`)
5. Open a Pull Request



## 👨‍💻 Author

**Jaime González Carbajo**

- GitHub: [@Jaime-GC](https://github.com/Jaime-GC)
- Project: [Orkestria](https://github.com/Jaime-GC/orkestria)

## 🙏 Acknowledgments

- Built as part of a Final Degree Project (TFG)

---

<p align="center">
  <i>Orchestrating projects, one task at a time</i> 🎼
</p>
