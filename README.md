# Hi, I'm Mohamed Ahmed Sayed 👋

**Junior .NET Backend Developer** · C# · ASP.NET Core · REST APIs · Entity Framework Core · SQL Server

I'm a junior .NET backend developer with a microbiology and chemistry degree, and I build backend systems in the domain I came from: the medical laboratory. I learn by building, and my main project is a medical laboratory system that I built twice, first as an MVC web app and then redesigned as a REST API with JWT authentication and role-based authorization.

I'm looking for my first junior .NET backend role where I can keep learning and contribute to real products.

## Featured Projects

### 🧪 [Medical Laboratory Management System API](https://github.com/mohamedsayed-1/medical-laboratory-management-system-API)
A REST API for managing patients, appointments, requested lab tests, and lab results.
- JWT authentication with ASP.NET Core Identity, and three roles (Admin, Receptionist, Technician) enforced through role-based authorization
- Appointment status is derived from its lab tests, and domain rules are enforced in the entities, not only in the services
- Business-rule violations return `409 Conflict`, kept separate from `404` and validation errors
- Soft delete with EF Core global query filters, and DTOs shaped per use case
- **Stack:** C#, ASP.NET Core Web API, EF Core, SQL Server, Swagger

### 🏥 [Medical Laboratory Management System (MVC)](https://github.com/mohamedsayed-1/medical-laboratory-management-system)
The first version of the same domain: a server-rendered web app for appointments, patients, doctors, and lab results.
- Per-entity service layer on a generic CRUD base, with referential-integrity checks
- Encapsulated domain rules, such as lab test results moving from `Queued` to `Completed` through entity methods
- **Stack:** C#, ASP.NET Core MVC, EF Core (Code First), SQL Server, Razor, Bootstrap

### 📚 [C++ Data Structures and Algorithms](https://github.com/mohamedsayed-1/cpp-data-structures-and-algorithms)
Core data structures and algorithms written from scratch in C++, with generic templates, the Rule of Three, and exception-based error handling.
- Arrays, linked lists, stacks, queues, a deque, hash tables, and a binary search tree
- Sorting, searching, graph traversal, shortest paths (Dijkstra, Bellman-Ford, Floyd-Warshall), and minimum spanning trees (Kruskal, Prim)

## Tech Stack

- **Languages:** C#, SQL, C/C++
- **Backend:** .NET, ASP.NET Core Web API, ASP.NET Core MVC, RESTful APIs, Middleware, Asynchronous Programming 
- **Data:** Entity Framework Core, LINQ, SQL Server, stored procedures, database design
- **Security:** ASP.NET Core Identity, JWT authentication, role-based authorization, Claims-Based Authorization, Policy-Based Authorization 
- **Concepts:** OOP, SOLID, Dependency Injection, DTOs, Separation of Concerns, Data Structures & Algorithms
- **Tools:** Git, GitHub, Postman, Swagger / OpenAPI, SQL Server Management Studio, Visual Studio, VS Code, NuGet

## Get in Touch

💼 [LinkedIn](https://www.linkedin.com/in/mohamedahmedsyd) · 🌐 Arabic (native), English (fluent)
