# Hi, I'm Carlos Monsalve 👋

### Senior Full Stack Engineer | TypeScript · React · Next.js · NestJS

I'm a Senior Full Stack Engineer focused on building scalable, maintainable, and business-driven software.

I have experience working across the full software development lifecycle, from understanding business requirements and designing software architecture to building backend services, REST APIs, modern frontend applications, database models, integrations, authentication systems, and deployment environments.

My main focus is turning complex business requirements into reliable software solutions using modern technologies, pragmatic architecture, and solid engineering practices.

---

## 👨‍💻 About Me

- 💻 Senior Full Stack Engineer
- ⚡ Specialized in TypeScript and modern web development
- 🏗 Interested in scalable and maintainable software architecture
- 🔌 Experience designing and developing REST APIs and backend services
- 🗄 Experience with relational databases, PostgreSQL and MySQL
- 🔐 Experience building authentication and authorization systems
- 🌐 Experience working across frontend and backend applications
- 🤖 AI-Assisted Development enthusiast

I enjoy understanding how a business works and translating its requirements into well-structured software that is easier to maintain and evolve.

---

## 🛠 Tech Stack

### Frontend

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?logo=react)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)
![Material UI](https://img.shields.io/badge/Material_UI-007FFF?logo=mui&logoColor=white)

### Backend

![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)

### Database & ORM

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white)

### Testing, Tools & Cloud

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github)
![Jest](https://img.shields.io/badge/Jest-C21325?logo=jest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white)

---

## 🏗 Engineering Approach

I believe good software should not only work today — it should also be understandable, maintainable, secure, and ready to evolve as business requirements change.

Some of the practices and concepts I work with:

- Clean Architecture
- Domain-Driven Design (DDD)
- Modular architecture
- REST API Design
- Repository Pattern
- Service and Application Layers
- Mapper Pattern
- Authentication & Authorization
- JWT
- OAuth2
- Role-Based Access Control (RBAC)
- Database Modeling
- Multi-tenant architectures
- Input Validation
- Error Handling
- Automated Testing
- Dockerized Development Environments

I prefer pragmatic engineering decisions over unnecessary complexity. Architecture should help the team build and maintain software, not become an obstacle.

---

## 💼 What I Work On

Throughout my career, I have worked on software solutions involving:

### Full-Stack Applications

Building applications where frontend and backend work together as a complete system, including user interfaces, APIs, authentication, data models, and business workflows.

### Backend Services & APIs

Designing and implementing REST APIs, application services, authentication systems, business rules, validation, error handling, and integrations with external services.

### Business & Administration Platforms

Developing backoffice and administration platforms used to manage business operations, data, users, products, customers, and internal workflows.

### Authentication & Security

Working with:

- JWT authentication
- OAuth2 integrations
- Google authentication
- Role-based authorization
- Secure HTTP cookies
- Input validation
- Protected routes and API endpoints

### Database Design

Working directly with relational databases and data models using:

- PostgreSQL
- MySQL
- Prisma ORM
- SQL

My experience includes designing relationships, constraints, indexes, tenant boundaries, and data models based on business requirements.

### Integrations

I have experience integrating applications with external platforms and services, including:

- AWS services
- Salesforce
- Email providers
- OAuth providers
- Cloud storage
- External REST APIs

---

## 🚀 Featured Project

### Commerce Platform

A full-stack multi-tenant SaaS platform designed to centralize commercial operations for organizations.

The platform acts as an internal **Commerce Command Center**, allowing organizations to manage:

- Products
- Customers
- Sales orders
- Suppliers
- Purchase orders
- Goods receipts

The project focuses on solving a common problem in small and medium-sized organizations: commercial information spread across spreadsheets and disconnected tools.

Each organization operates independently, with data isolation enforced throughout the application.

### Key Engineering Highlights

- Multi-tenant architecture with organization-scoped data
- Users can belong to multiple organizations
- Membership roles: `OWNER`, `ADMIN`, and `MEMBER`
- Modular backend architecture
- Pragmatic DDD and Clean Architecture
- Business rules encapsulated in the domain
- Historical snapshots for sales order products
- Controlled order lifecycle transitions
- Partial and complete goods receipts
- Stock updates triggered by goods receipts
- Consistent API response and error formats
- JWT authentication using secure httpOnly cookies
- Internationalized frontend in Spanish, English, and French
- End-to-end testing for public application routes

### AI-Assisted Operations

The project also explores responsible AI integration as an optional assistant rather than as an autonomous decision-maker.

The platform integrates:

- Google Gemini
- OpenAI

AI capabilities are designed to assist users with:

- Operational summaries
- Contextual section summaries
- Guided operational searches
- Connector availability checks

The AI layer is read-only and cannot:

- Modify business data
- Create records
- Modify stock
- Change order states
- Execute arbitrary database queries
- Bypass multi-tenant isolation

The project also includes a deterministic supply review that identifies low-stock products and evaluates pending purchase orders without relying on an LLM.

### Project Documentation

The repository is organized as a monorepo with dedicated documentation at different levels:

- 📘 [Project Overview](https://github.com/devCarlosMonsalve/commerce-platform) — Overall architecture, project scope, business context, and how the frontend and backend work together.
- 🖥️ [Frontend Documentation](https://github.com/devCarlosMonsalve/commerce-platform/blob/main/frontend-mmp/README.md) — Frontend architecture, application structure, UI, internationalization, authentication flow, and testing.
- ⚙️ [Backend Documentation](https://github.com/devCarlosMonsalve/commerce-platform/blob/main/backend-mmp/README.md) — Backend architecture, API, domain logic, multi-tenancy, database design, security, and AI integrations.

---

## 🧠 Backend & Architecture

I enjoy backend engineering because it sits at the intersection of business requirements and technical decisions.

When building backend systems, I usually think about:

1. What business problem are we solving?
2. What are the important business rules?
3. What data needs to exist?
4. What relationships and constraints should the database enforce?
5. Where should the business logic live?
6. How should the API expose the functionality?
7. How do we protect authentication and authorization?
8. How can the system evolve without becoming difficult to maintain?

I particularly enjoy working with modular architectures where business domains have clear responsibilities and infrastructure concerns remain separated from core business logic when appropriate.

---

## 🌐 Full-Stack Development

I enjoy working across the full stack because it gives me a broader understanding of how software systems work end to end.

A feature often involves more than implementing a UI or writing an API endpoint.

It can involve:

- Understanding the business requirement
- Designing the data model
- Defining business rules
- Implementing backend services
- Designing API contracts
- Building the frontend interface
- Handling authentication and authorization
- Managing loading and error states
- Testing the workflow
- Integrating external services

Having experience across these areas helps me understand the impact of technical decisions beyond a single layer of the application.

---

## 🤖 AI-Assisted Development

I actively incorporate AI-assisted development tools into my engineering workflow.

Tools I use include:

- ChatGPT
- GitHub Copilot
- Cursor

I use AI to support areas such as:

- Software design
- Architecture discussions
- Code implementation
- Refactoring
- Code reviews
- Test generation
- Debugging
- Documentation
- Exploring technical alternatives

I see AI as an engineering tool, not a replacement for technical judgment.

The responsibility for architecture, correctness, security, maintainability, and business decisions remains with the engineer.

---

## 📈 Currently Exploring

I'm continuously improving my skills and exploring areas such as:

- Software architecture
- Advanced TypeScript patterns
- Scalable backend systems
- AI-assisted software development
- Responsible LLM integration
- Multi-tenant SaaS architectures
- System design
- Cloud-native development

---

## 🤝 Collaboration

I enjoy working with people from different technical and professional backgrounds.

Beyond software development, I have also taught dance classes, which helped me develop communication, patience, and the ability to adapt explanations depending on the person and their experience level.

Those skills have also influenced how I work in engineering teams. I enjoy sharing knowledge, discussing ideas, helping teammates, and learning from different perspectives.

---

## 📫 Let's Connect

I'm open to connecting with developers, engineering teams, and opportunities where I can contribute to building high-quality software.

<p align="left">
  <a href="https://linkedin.com/in/carlosmonsalveb">
    <img src="https://img.shields.io/badge/LinkedIn-Carlos%20Monsalve-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/DevCarlosMonsalve">
    <img src="https://img.shields.io/badge/GitHub-DevCarlosMonsalve-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="mailto:monsalvecarlos@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

> Building scalable, maintainable, and business-driven software through pragmatic engineering and continuous learning.