# Hi, I'm Carlos Monsalve 👋

### Senior Full Stack Engineer | TypeScript · Next.js · NestJS

I'm a Senior Full Stack Engineer focused on building scalable, maintainable, and business-driven web applications.

I have experience working across the full software development lifecycle, from software architecture and backend services to modern frontend applications, authentication, integrations, and database design.

My main focus is building reliable software using modern technologies, clean architecture principles, and pragmatic engineering practices.

---

## 👨‍💻 About Me

- 💻 Senior Full Stack Engineer
- ⚡ Specialized in TypeScript and modern web development
- 🏗 Interested in scalable and maintainable software architecture
- 🔌 Experience designing and developing REST APIs
- 🗄 Experience working with PostgreSQL and MySQL
- 🔐 Experience with authentication and authorization systems
- 🤖 AI-Assisted Development enthusiast

I enjoy transforming business requirements into well-structured, maintainable, and reliable software solutions.

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

### Tools & Cloud

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github)
![Jest](https://img.shields.io/badge/Jest-C21325?logo=jest&logoColor=white)

---

## 🏗 Engineering Approach

I believe good software should not only work — it should also be understandable, maintainable, and ready to evolve.

Some of the practices and concepts I work with:

- Clean Architecture
- Domain-Driven Design (DDD)
- Modular Monolith Architecture
- REST API Design
- Repository Pattern
- Service Layer
- Mapper Pattern
- Authentication & Authorization
- JWT
- OAuth2
- Role-Based Access Control (RBAC)
- Database Modeling
- Input Validation
- Automated Testing
- Dockerized Development Environments
- AI-Assisted Development

---

# 🚀 Featured Project

## 🛒 [Commerce Platform](https://github.com/DevCarlosMonsalve/commerce-platform)

A multi-tenant SaaS platform designed to centralize commercial operations for small and medium-sized businesses, distributors, and sales, administration, purchasing, and supply teams.

Commerce Platform is not a public e-commerce store.

It works as an internal **Commerce Command Center**, allowing organizations to manage their commercial operations from a centralized platform.

**MANAGE → MONITOR → UNDERSTAND → ACT**

The project addresses the problem of having products, customers, sales orders, suppliers, and purchasing information scattered across spreadsheets or disconnected tools.

Each organization operates independently within the same platform.

---

## 🎯 What the Platform Manages

- Product management
- Customer management
- Sales order management
- Supplier management
- Purchase order management
- Partial goods receipts
- Complete goods receipts
- Organization memberships
- Multi-organization users
- Operational dashboards
- AI-assisted operational insights
- Deterministic supply review

The application supports users belonging to multiple organizations while maintaining strict data isolation between tenants.

---

## 👥 Target Users

Commerce Platform is designed for:

- Small and medium-sized commercial businesses
- Distributors
- Sales teams
- Administrative teams
- Purchasing teams
- Supply and operations teams

A user can belong to multiple organizations and operate within an isolated organization context.

---

## 🏗 Architecture

Commerce Platform follows a **Modular Monolith** architecture with independent frontend and backend applications.

### Applications

- `frontend-mmp` — Next.js web application
- `backend-mmp` — NestJS REST API
- PostgreSQL — Primary relational database
- Docker Compose — Local database environment

The architecture keeps clear boundaries between business modules while avoiding unnecessary microservices.

### Main Business Modules

- Authentication & Identity
- Organizations & Memberships
- Products
- Customers
- Sales Orders
- Suppliers
- Purchase Orders
- Goods Receipts
- AI Operational Assistance
- Health
- Prisma & Persistence

Frontend and backend communicate through HTTP using a REST API.

---

## 🖥 Frontend

The frontend is built with:

- Next.js 16
- React 19
- TypeScript
- Material UI 9
- Tailwind CSS 4
- next-intl
- Axios
- Playwright

### Frontend Responsibilities

- Localized landing page
- User registration
- Login and logout
- Active organization selection
- Active organization persistence
- Operational dashboard
- Product management
- Customer management
- Sales order management
- Supplier management
- Purchase order management
- Partial goods receipts
- Complete goods receipts
- Loading states
- Error states
- Empty states
- Not-found states

The interface is available in:

- Spanish
- English
- French

The frontend communicates with the backend using Axios with credentials enabled, allowing authentication cookies to be sent securely.

The application also includes a global operational assistance drawer so AI capabilities remain secondary to the main product workflows.

---

## ⚙️ Backend

The backend is built with:

- NestJS 11
- TypeScript
- Prisma 6
- PostgreSQL 16
- Passport JWT
- `@nestjs/jwt`
- bcryptjs
- class-validator
- class-transformer
- Helmet
- CORS
- Throttling
- Jest
- Supertest

The REST API uses the `/api` prefix.

### API Response Format

Successful responses follow a consistent structure:

`{ success: true, data, message? }`

Error responses follow:

`{ success: false, statusCode, message, path, timestamp }`

### Cross-Cutting Concerns

The backend includes:

- JWT authentication
- httpOnly cookies
- DTO validation
- CORS with credentials
- Global exception handling
- Request logging
- Rate limiting
- Authentication guards
- Organization membership validation
- Role-based authorization

---

## 🧩 Backend Architecture

The backend applies **Domain-Driven Design and Clean Architecture pragmatically**, keeping the system structured without introducing unnecessary abstractions.

The main dependency direction is:

**Presentation → Application → Domain**

Infrastructure provides the concrete implementations required by the inner layers.

### Typical Module Structure

#### Domain

- Business entities
- Business rules
- Domain errors
- Repository contracts

#### Application

- DTOs
- Use cases
- Application workflows

#### Infrastructure

- HTTP controllers
- Prisma repositories
- Persistence implementations
- External adapters

### Key Principles

- Controllers remain thin and focused on HTTP concerns.
- Controllers validate DTOs and delegate execution to use cases.
- Use cases coordinate application workflows.
- Important business rules live in domain entities and domain logic.
- Repository contracts belong to the inner layers.
- Prisma remains an infrastructure concern.
- The domain does not depend on NestJS, HTTP, Prisma, or PostgreSQL.
- Entities are not treated as simple mutable data containers when relevant business behavior exists.

---

## 🏢 Multi-Tenant Architecture

`Organization` represents the tenant boundary.

Every business operation follows the same context:

**Authenticated User → Active Organization → Membership Validation → Use Case → Organization-Scoped Data**

This means that:

- A user can belong to multiple organizations.
- Each organization operates independently.
- Business data is always isolated by `organizationId`.
- A user from one organization cannot access or modify data belonging to another organization.

### Membership Roles

- `OWNER`
- `ADMIN`
- `MEMBER`

Products, customers, sales orders, suppliers, purchase orders, and goods receipts operate within an organization context.

Multi-tenant isolation is enforced throughout the application flow, not only at the user interface level.

---

## 📦 Sales Order Domain

Sales orders contain business rules that are enforced by the domain.

### Order Rules

- An order belongs to an organization.
- An order belongs to a customer.
- The customer must belong to the active organization.
- Products included in an order must belong to the active organization.
- Orders preserve historical product information.
- Orders cannot be arbitrarily modified once their lifecycle progresses.

### Historical Product Snapshots

Order items preserve:

- Product ID
- Product name
- SKU
- Description
- Unit price

This prevents future catalog changes from modifying historical orders.

### Order Lifecycle

**DRAFT → PENDING → CONFIRMED → COMPLETED**

Orders can be cancelled before completion.

State transitions are controlled by domain behavior rather than allowing controllers or DTOs to modify the status directly.

---

## 🚚 Purchasing & Goods Receipts

The purchasing workflow supports:

- Supplier management
- Purchase order creation
- Organization-scoped products
- Partial goods receipts
- Complete goods receipts
- Durable receipt history
- Stock updates after goods are received

### Business Rules

- Purchase orders belong to the active organization.
- Suppliers must belong to the active organization.
- Products must belong to the active organization.
- Received quantities cannot exceed requested quantities.
- Each receipt remains registered as historical information.
- Registering a receipt increases the corresponding product stock.

---

## 🗄 Database & Persistence

Commerce Platform uses:

- PostgreSQL 16
- Prisma ORM
- Docker Compose for local database provisioning

Prisma defines the database schema, manages migrations, and provides the database client.

### Main Entities

- User
- Organization
- Membership
- Product
- Customer
- Order
- OrderItem
- Supplier
- PurchaseOrder
- PurchaseOrderItem
- PurchaseReceipt
- PurchaseReceiptItem

`Organization` is the tenant boundary.

Business resources are associated with an organization through `organizationId`.

Relevant constraints include:

- A user can only have one membership per organization.
- SKU values are unique within the same organization.
- Business data is scoped by organization.
- Relevant indexes support organization-scoped queries and main relationships.
- Monetary values use decimal database columns to preserve financial precision.

---

# 🤖 AI Operational Assistance

The platform includes optional AI-assisted capabilities designed to help users understand operational information.

AI is not a source of truth and cannot execute business operations.

The AI integration is intentionally assistive and secondary to the main workflows.

### Providers

The application integrates two text generation providers through a provider-neutral contract:

- Google Gemini as the primary provider
- OpenAI as a sequential fallback

Technologies include:

- `@google/genai`
- `openai`
- Gemini Interactions API
- OpenAI Responses API

This keeps provider-specific SDKs outside the core application logic.

---

## 🧠 AI Capabilities

AI-assisted functionality is available to:

- `OWNER`
- `ADMIN`

Capabilities include:

1. AI connector verification
2. Organization operational summaries
3. Contextual summaries for:
   - Products
   - Sales orders
   - Purchase orders
4. Guided operational search using natural language
5. Supply review

The AI is designed to help users understand existing operational data rather than autonomously control the business.

---

## 🔐 AI Safety Model

The AI layer cannot:

- Execute SQL
- Generate arbitrary Prisma queries
- Create records
- Modify stock
- Modify orders
- Change business states
- Bypass multi-tenant isolation

Operational search uses a closed set of supported intents:

- Products without stock
- Pending sales orders
- Open purchase orders
- Unsupported query

The LLM is only responsible for identifying the supported intent.

The backend executes predefined queries and always scopes results by `organizationId`.

---

## 🔒 Data Minimization

Operational summaries sent to the LLM use aggregated metrics.

The application does not send:

- Customer names
- User data
- Internal IDs
- Detailed order content
- Financial values
- Sensitive business information

This approach keeps AI functionality useful while reducing unnecessary exposure of business data.

---

## ⏱ Provider Availability Handling

AI providers may temporarily become unavailable.

For example:

- Gemini may return temporary quota limits.
- OpenAI may be unavailable or have insufficient credits.

When the primary provider indicates a retry period and the fallback provider also fails:

- The backend returns a `503` response.
- The response includes `retryAfterSeconds`.
- The frontend displays a localized message.
- The AI drawer shows a countdown.
- LLM-dependent actions are temporarily disabled.
- Internal provider details and credentials remain hidden.

The rest of the platform remains independent from AI availability.

---

## 📊 Deterministic Supply Review

Supply review does not depend on Gemini or OpenAI.

It is a deterministic backend capability designed to identify products that may require purchasing attention.

The review identifies active products with stock less than or equal to five units.

### Priority Levels

- `CRITICAL` — Stock is zero or negative.
- `ATTENTION` — Stock is between one and five units.

### Information Returned

For each relevant product, the review includes:

- Priority
- Current stock
- SKU
- Number of open purchase orders
- Units pending to be received
- Recommended action

Pending units are calculated as:

**orderedQuantity - receivedQuantity**

### Recommended Actions

- `CREATE_PURCHASE_ORDER`
- `REVIEW_OPEN_PURCHASE_ORDERS`

The system does not:

- Create purchase orders automatically.
- Invent quantities to purchase.
- Recommend suppliers without sufficient data.
- Replace human decision-making.

The supply review remains explainable and requires human review.

---

## 🔌 AI Endpoints

The AI module exposes endpoints such as:

- `GET /api/organizations/:orgId/ai/connectors/verify`
- `GET /api/organizations/:orgId/ai/operations-summary`
- `GET /api/organizations/:orgId/ai/operations-summary/:section`
- `POST /api/organizations/:orgId/ai/operations/search`
- `GET /api/organizations/:orgId/ai/purchase-suggestions`

---

## 🧪 Testing

The project includes automated testing using:

### Backend

- Jest
- Supertest

### Frontend

- Playwright

Testing is used to support application reliability across backend behavior and public frontend routes.

---

## 🔧 Project Structure

The project is composed of independent frontend and backend applications:

- `frontend-mmp`
- `backend-mmp`

This separation allows frontend and backend concerns to evolve independently while maintaining a clear HTTP integration boundary.

The backend remains organized around business domains rather than technical layers alone.

---

## 🚀 Project Highlights

- 🏢 Multi-tenant SaaS architecture
- 🔐 Organization-scoped data isolation
- 👥 Multi-organization users and membership roles
- 📦 Product and customer management
- 🧾 Sales order lifecycle
- 🚚 Supplier and purchase order management
- 📥 Partial and complete goods receipts
- 📊 Deterministic supply review
- 🏗 Modular Monolith architecture
- 🧩 Pragmatic DDD and Clean Architecture
- 🔒 JWT authentication using httpOnly cookies
- 🌍 Internationalization in Spanish, English, and French
- 🤖 Optional AI-assisted operational insights
- 🧠 Gemini primary provider with OpenAI fallback
- 🛡 AI safety boundaries and tenant isolation
- 🐳 Dockerized PostgreSQL development environment

---

## 🔗 Repository

### 🛒 [Commerce Platform](https://github.com/DevCarlosMonsalve/commerce-platform)

> Currently under active development.

---

# 💼 Professional Background

Throughout my career, I have worked on software solutions involving:

- Full-stack web development
- Administration and backoffice platforms
- REST APIs and backend services
- Authentication and authorization
- Database design
- Third-party integrations
- Cloud services
- Multi-tenant platforms
- Digital wallets and loyalty solutions

My experience includes working with modern JavaScript and TypeScript ecosystems as well as backend technologies such as PHP and Laravel.

---

# 🤖 AI-Assisted Development

I actively incorporate AI-assisted development tools into my engineering workflow.

Tools I use include:

- ChatGPT
- GitHub Copilot
- Cursor

I use AI to support:

- Software design
- Architecture discussions
- Code implementation
- Refactoring
- Code reviews
- Test generation
- Debugging
- Documentation

I see AI as a tool that helps accelerate development while responsibility for architecture, security, quality, and engineering decisions remains with the developer.

---

# 📫 Let's Connect

I'm always open to connecting with developers, engineering teams, and new opportunities.

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

> Building scalable, maintainable software with a focus on clean architecture, strong domain boundaries, and real business value.
