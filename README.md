# ASP.Net Core Angular Social Media Website

A full-stack social media web application built using ASP.NET Core and Angular. The project demonstrates a modern client-server architecture where an Angular SPA communicates with a RESTful ASP.NET Core API to manage user interactions and social features. It serves as a practical example of building scalable, data-driven web applications using the .NET ecosystem and modern frontend tooling.

---

## Badges

![Repo Size](https://img.shields.io/github/repo-size/drussell33/ASP.Net-Core-Angular-Social-Media-Website)
![Last Commit](https://img.shields.io/github/last-commit/drussell33/ASP.Net-Core-Angular-Social-Media-Website)
![Top Language](https://img.shields.io/github/languages/top/drussell33/ASP.Net-Core-Angular-Social-Media-Website)

---

## Key Features

- Full-stack application using ASP.NET Core API and Angular SPA
- User authentication and account management
- Social media-style interactions (posts, profiles, feeds)
- Client-server communication via HTTP APIs
- Structured backend with controllers and services
- Angular-based frontend with component-driven architecture
- Persistent data storage via relational database
- Separation of concerns between frontend and backend layers

---

## Tech Stack

### Backend
- ASP.NET Core Web API
- C#
- Entity Framework Core

### Frontend
- Angular
- TypeScript
- HTML / CSS

### Database
- Relational database (configured via connection string in ASP.NET Core)

### Tools / Services
- .NET SDK
- Node.js / npm
- Angular CLI
- Visual Studio / VS Code
- Git & GitHub

---

## Architecture Overview

This project follows a typical **client-server architecture**:

- The **Angular frontend** acts as a Single Page Application (SPA), handling UI rendering, routing, and user interaction.
- The **ASP.NET Core backend** exposes RESTful API endpoints for data access and business logic.
- The **database layer** persists user data, posts, and application state.

### Data Flow

1. User interacts with Angular UI
2. Angular sends HTTP requests to ASP.NET Core API
3. Controllers process requests and delegate to services
4. Services interact with the database via Entity Framework Core
5. API returns JSON responses
6. Angular updates UI accordingly

### Design Patterns Observed

- Controller-based API design
- Dependency Injection (built into ASP.NET Core)
- Service layer abstraction
- DTO-based data transfer (typical in ASP.NET APIs)
- Component-based frontend architecture (Angular)

---

## Project Structure

```bash
ASP.Net-Core-Angular-Social-Media-Website/
│
├── API/                     # ASP.NET Core backend
│   ├── Controllers/         # API endpoints
│   ├── Models/              # Domain models / entities
│   ├── Data/                # DbContext and database logic
│   ├── Services/            # Business logic layer
│   └── appsettings.json     # Configuration
│
├── ClientApp/               # Angular frontend
│   ├── src/
│   │   ├── app/             # Angular components, services
│   │   ├── assets/          # Static assets
│   │   └── environments/    # Environment configs
│   ├── angular.json         # Angular config
│   └── package.json         # Node dependencies
│
├── *.sln                    # Solution file
└── README.md
```

---

## Getting Started

### Prerequisites

- .NET SDK (6.0 or later recommended)
- Node.js (16+ recommended)
- Angular CLI
- SQL Server or compatible database

---

### Installation

```bash
# Clone the repository
git clone https://github.com/drussell33/ASP.Net-Core-Angular-Social-Media-Website.git

cd ASP.Net-Core-Angular-Social-Media-Website
```

---

### Backend Setup

```bash
cd API

# Restore dependencies
dotnet restore

# Run the API
dotnet run
```

---

### Frontend Setup

```bash
cd ClientApp

# Install dependencies
npm install

# Run Angular app
ng serve
```

---

### Usage

- Backend API runs on: https://localhost:<port>
- Frontend runs on: http://localhost:4200
- Angular communicates with the API via HTTP requests

---

## Roadmap

- [x] Initial ASP.NET Core + Angular setup
- [x] Basic API structure and endpoints
- [x] Angular SPA integration
- [ ] User authentication improvements
- [ ] Enhanced UI/UX design
- [ ] Real-time features (chat/notifications)
- [ ] Media uploads (images/videos)
- [ ] Deployment configuration (Docker / Cloud)
- [ ] Unit and integration testing

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your fork
5. Open a Pull Request

---

## Screenshots / Demo

*Screenshots and demo content can be added here.*

---

## Contact

GitHub: https://github.com/drussell33

---

## License

No license file was found in the repository.
