# Romil Lakhani
**Computer Programming & Analysis Honours Graduate — Seneca Polytechnic**

Software developer with experience building full-stack backend APIs, JavaFX desktop applications, REST microservices, iOS mobile apps, AI-integrated services, and C/C++ systems applications. Comfortable with RESTful API design, database-backed CRUD workflows, Docker-based environments, CI/CD automation, AWS integrations, and automated testing. Repositories below highlight implemented features, validations, and end-to-end application workflows.

---

## 🎯 Focus Areas
- Backend development (REST APIs, authentication, data persistence)
- Cloud-ready services (containerization, CI/CD, AWS integrations)
- AI-integrated services (RAG patterns, LLM API integration, structured data retrieval)
- Mobile apps (SwiftUI / Core Data)
- Quality-minded development (validation, testing, debugging, production-readiness)

---

## 📂 Projects

### Backend / Cloud

#### Smart Inventory Query API
- Built a production-grade REST API using **FastAPI** and **Python 3.x** to manage an aircraft parts inventory with full CRUD operations, Pydantic request validation, and auto-generated Swagger documentation.
- Wrote and optimized complex **SQL queries**, joins, CTEs, aggregation views, and stored procedures in SQLite to support application logic, analytics, and assembly stock-readiness checks.
- Integrated the **Claude AI API** as a RESTful third-party service to deliver a RAG-style natural language query endpoint — structured SQL data retrieved at runtime and injected as context for intelligent responses.
- Delivered a complete **pytest** test suite (11 tests) covering all endpoints, edge cases, and error states, ensuring production-ready reliability.

#### Fragments Microservice
- Developed an **Express-based REST API** with request validation, structured logging, and user ID hashing.
- Containerized the service with **Docker** and used **Docker Compose** to run an integrated multi-container local environment.
- Implemented **CI/CD** to automatically build, tag, and push container images on each git push via GitHub Actions.
- Integrated **AWS services** (Cognito for auth, S3 for object storage, DynamoDB for data persistence) and used AWS CLI/SDKs for service interaction.
- Added integration testing and local development support by simulating AWS dependencies offline.

---

### Desktop (JavaFX)

#### Hotel Reservation System
- Built a **JavaFX** kiosk application to manage hotel check-ins, bookings, and billing.
- Implemented **MySQL-backed** availability validation to prevent double bookings across room types.
- Designed input validation and error handling to keep transactions reliable in a self-service flow.

#### Auto Loan Application
- Built a **JavaFX** calculator for weekly, bi-weekly, and monthly loan payment options.
- Reduced input errors using sliders, choice boxes, and alert-driven validation.
- Implemented secure **MySQL** authentication and multi-tier financial algorithms for complex interest rate calculations.

#### Inventory Management System
- Built a **JavaFX** desktop application to manage parts and products with **MySQL** persistence.
- Implemented search by ID and name with comprehensive validation.
- Enforced cross-record validation rules to prevent invalid updates and inconsistent inventory states.

#### Aircraft Inventory Management System
- Built a **Java** application to manage, track, and assemble 200+ aircraft parts using component-based product composition logic.
- Designed complex SQL joins, views, and referential integrity validation to prevent invalid inventory states.
- Implemented secure user authentication and iterative refactoring of data access logic across development cycles.

---

### Mobile (iOS — SwiftUI)

#### Tax Filing Management — iOS
- Built an **iOS** application using **SwiftUI** and **Core Data** to manage tax client workflows.
- Implemented role-based access, form validation, and persistent storage for admin and customer views.
- Designed an admin dashboard with status indicators and profile management to track filing progress.

#### Book Collection Manager — iOS
- Built an **iOS** application using **SwiftUI** and **Core Data** to manage personal book collections.
- Implemented full CRUD with real-time search, favorites, and persistent storage.
- Designed navigation with detail views, edit sheets, swipe actions, and state-driven UI validation.

#### Straw Hat Pirates Crew Registration — iOS
- Developed a **SwiftUI** form-based app with input validation and credential checks.
- Implemented secure password visibility toggling, alerts, and reset logic.
- Built a profile screen with reusable components and state-driven UI updates.

---

### Systems / C++

#### Truck Inventory & Logistics Allocation System
- Developed a **C/C++** modular logistics system to allocate trucks by route, capacity, and schedule.
- Implemented multi-variable allocation algorithms with partial fulfillment logic and stock validation.
- Led a team of 4 developers using **Git** and **Jira** across a 3-month delivery cycle with full test coverage.

#### Assembly Line Application
- Developed a queue-based **C++** system to simulate production workflows and order fulfillment.
- Implemented partial fulfillment logic and stock checks for incomplete inventory scenarios.
- Structured the application using modular components to improve maintainability and error handling.

#### Point of Sale System
- Developed a console-based **C++** POS system to manage inventory, sales transactions, and receipt generation.
- Implemented stock tracking and validation to prevent overselling and handle low inventory scenarios.
- Optimized transaction workflows to reduce manual input and improve checkout efficiency.

---

## 🛠️ Tech Stack
- **Languages:** Java, Python (3.x), C, C++, C#, Swift, SQL, JavaScript, HTML, CSS
- **Backend / Frameworks:** FastAPI, Express.js, Node.js, Spring Boot (foundational), REST APIs, microservice architecture
- **Databases:** SQLite, MySQL, MongoDB, Firebase, PostgreSQL
- **AI / Data:** Claude API, RAG-style retrieval, ETL scripting, Pandas, Python for ML
- **Cloud / DevOps:** AWS (Cognito, S3, DynamoDB), Docker, Docker Compose, GitHub Actions (CI/CD), Git, Jira
- **Mobile:** iOS (SwiftUI, Core Data, Xcode)
- **Other:** JavaFX, pytest, JUnit-style testing, technical documentation

---

## 🧰 Tools & Practices
- **Cloud:** AWS (Cognito, S3, DynamoDB), AWS CLI/SDKs, Docker, CI/CD pipelines
- **Testing:** Unit testing, integration testing, functional & regression testing, pytest automation
- **Delivery:** Full SDLC, Agile concepts, requirements assessment, gap analysis, documentation and handoff
- **Tools:** VS Code, PyCharm, IntelliJ/NetBeans, Xcode, Jira, SSH, MS Office Suite

---
