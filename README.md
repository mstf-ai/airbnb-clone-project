# AirBnB Clone Project

## 📌 Project Overview
The **AirBnB Clone Project** is a step-by-step journey to build a simplified version of the AirBnB platform.  
It focuses on learning core software engineering concepts, teamwork, and building scalable applications.

## 🎯 Goals
- Understand the foundations of back-end development.  
- Practice working with **Git/GitHub** and collaborative workflows.  
- Build a functional clone of AirBnB with key features.  
- Apply clean code practices and documentation standards.  

## 🛠️ Tech Stack
- **Python** (core logic & back-end development)  
- **Flask** (web framework)  
- **SQLAlchemy / MySQL** (database management)  
- **HTML, CSS, JavaScript** (front-end basics)  
- **Git & GitHub** (version control & collaboration)  

## 🚀 Progress
This repository will be updated incrementally as we implement new features of the project. Each stage will reflect growth in functionality and engineering practices.
---
## 🎨 UI/UX Design Planning

### 🌟 Design Goals
- Create a clean, intuitive, and user-friendly interface.  
- Ensure seamless navigation between listings, details, and booking.  
- Prioritize clarity, responsiveness, and accessibility for all devices.  
- Build a visually appealing design that aligns with the AirBnB experience.  

### 🔑 Key Features
- Easy-to-navigate property listings with search and filters.  
- Clear presentation of property details (price, amenities, reviews).  
- Smooth checkout process with minimal steps to confirm booking.  

### 📄 Primary Pages

| Page                     | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| **Property Listing View** | Displays a grid/list of available properties with images, pricing, and location info. |
| **Listing Detailed View** | Shows full details of a selected property including images, amenities, host details, and reviews. |
| **Simple Checkout View**  | A streamlined booking form for entering guest details, payment, and confirming the reservation. |

### 💡 Why User-Friendly Design Matters
A user-friendly design is critical in a booking system because it:  
- Builds **trust** by making the process clear and transparent.  
- Reduces **friction** so users can book quickly without confusion.  
- Enhances **conversion rates**, turning visitors into customers.  
- Provides a **positive experience**, encouraging repeat use and referrals.  
---
### 🎨 Design Properties from Figma

#### 🎨 Color Styles
- **Primary Color:** #FF385C (Airbnb red-pink tone for buttons and highlights)  
- **Secondary Color:** #222222 (Dark gray for text and headers)  
- **Background Color:** #FFFFFF (Clean white background for readability)  
- **Accent Color:** #717171 (Light gray for secondary text/icons)  
- **Success/Confirmation Color:** #00A699 (Green tone for positive actions)  

#### ✍️ Typography
- **Font Family:** Circular (Airbnb standard) or fallback: Arial, Helvetica, sans-serif  
- **Font Weights:**  
  - Light (300) – Secondary text  
  - Regular (400) – Body content  
  - Medium (500) – Labels and small highlights  
  - Bold (700) – Titles and buttons  

- **Font Sizes:**  
  - 12px – Captions, small labels  
  - 14px – Secondary text  
  - 16px – Standard body text  
  - 20px – Subheadings  
  - 24px – Page titles  
  - 32px+ – Hero headlines  

---

### 💡 Importance of Identifying Design Properties
Identifying design properties in a mockup is essential because it:  
- Ensures **consistency** across all pages and components.  
- Helps developers translate UI into accurate code.  
- Saves time by reducing guesswork during implementation.  
- Strengthens brand identity by following a clear style guide.  
- Improves collaboration between designers and developers.  
---
## 👥 Project Roles and Responsibilities

To ensure smooth collaboration and successful delivery of the Airbnb Clone Project, the following roles and responsibilities are defined:

| **Role**             | **Key Responsibilities** |
|-----------------------|---------------------------|
| **Project Manager**   | Oversees the entire project lifecycle, coordinates between teams, manages deadlines, and ensures goals are met. |
| **Product Owner**     | Defines the product vision, prioritizes features, manages the product backlog, and ensures the final product meets user needs. |
| **Scrum Master**      | Facilitates Agile processes, removes obstacles, ensures team adherence to Scrum practices, and supports continuous improvement. |
| **Frontend Developers** | Implement the user interface, ensure responsiveness, integrate APIs with the frontend, and create accessible, user-friendly experiences. |
| **Backend Developers** | Build and maintain the server-side logic, manage databases, develop APIs, ensure scalability and performance. |
| **Designers (UI/UX)** | Create wireframes, prototypes, and mockups, define the visual identity, and ensure usability and accessibility across the platform. |
| **QA/Testers**        | Test features, report bugs, perform regression testing, validate design implementation, and ensure overall quality assurance. |
| **DevOps Engineers**  | Manage CI/CD pipelines, deployment, monitoring, and scaling of applications, ensuring reliability and security. |

---

### ✨ How Each Role Contributes to Success
- **Alignment:** Ensures every team member has a clear purpose.  
- **Efficiency:** Avoids overlapping tasks and improves workflow.  
- **Quality:** Distributes accountability for performance, usability, and security.  
- **Agility:** Supports iteration and fast delivery by leveraging cross-functional roles.  
---
## 🧩 UI Component Patterns

To ensure a consistent, reusable, and scalable design, the Airbnb Clone will adopt a **component-based approach**. Below are the key UI components we plan to create:

### 🔹 Core Components
1. **Navbar (Navigation Bar)**  
   - Provides quick access to main sections (Home, Listings, Checkout, Profile).  
   - Includes logo, search bar, and user account menu.  
   - Stays fixed at the top for easy navigation.  

2. **Property Card**  
   - Displays essential details about a property (image, title, price per night, rating).  
   - Allows users to preview properties at a glance.  
   - Responsive design to ensure consistency across devices.  

3. **Footer**  
   - Contains links to key information (About, Contact, Help, Terms & Privacy).  
   - May include social media icons and newsletter subscription.  
   - Maintains branding consistency at the bottom of all pages.  

---

### 🎯 Importance of Component Patterns
- **Reusability:** Components can be reused across multiple pages, reducing redundancy.  
- **Consistency:** Ensures uniform design and behavior across the app.  
- **Scalability:** New features can be added easily by extending existing patterns.  
- **Maintainability:** Isolating UI elements makes debugging and updating simpler.  
---
Based on common software development team structures and best practices.
> **Note:** On a small/student project, one person may wear multiple hats (e.g., PO + PM + Dev + QA). Roles above describe responsibilities rather than headcount.
## 👥 Team Roles

This project follows a clear division of responsibilities to keep delivery smooth and quality high.

| Role | What They Do | How They Contribute |
|---|---|---|
| **Product Owner** | Owns the product vision, prioritizes the backlog, clarifies requirements and acceptance criteria. | Ensures the team builds the highest-value features first and stays aligned with user needs. |
| **Scrum Master** | Facilitates Agile ceremonies, removes impediments, coaches the team on Scrum. | Improves flow, focus, and continuous improvement. |
| **Project Manager** | Plans timelines/scope, coordinates stakeholders, manages risks and communications. | Keeps the project on schedule and within scope. |
| **Software Architect** | Defines system architecture, tech choices, and cross-cutting concerns (security, scalability). | Provides a coherent technical blueprint that reduces rework. |
| **Backend Developer** | Implements server-side logic, APIs, integrations, and business rules; ensures performance and security. | Powers core functionality and reliable data flows. |
| **Frontend Developer** | Builds the UI in HTML/CSS/JS (and/or a framework), integrates with APIs, ensures responsiveness and accessibility. | Delivers an intuitive, performant user experience. |
| **Database Administrator (DBA)** | Designs schemas, manages migrations, backups, indexing, and data security. | Guarantees data integrity, availability, and query performance. |
| **UI/UX Designer** | Produces user flows, wireframes, mockups, and prototypes; defines visual styles and interactions. | Improves usability and consistency, reducing friction for users. |
| **QA / Test Engineer** | Plans and executes test strategies (unit, integration, E2E), regression, and automation; tracks defects. | Prevents bugs from reaching users and safeguards quality. |
| **DevOps Engineer** | Sets up CI/CD, infrastructure as code, monitoring/logging, and secure deployments. | Enables fast, reliable releases and operational stability. |
| **Business Analyst** | Elicits/clarifies requirements, documents processes, aligns business goals with technical solutions. | Reduces ambiguity and ensures features meet real needs. |
---
## 🛠️ Technology Stack

This project uses a modern stack to build a scalable, secure, and feature-rich Airbnb Clone.

| Technology | Purpose in Project |
|------------|--------------------|
| **Django** | A high-level Python web framework used to build the backend, define business logic, and expose RESTful/GraphQL APIs. |
| **Django REST Framework (DRF)** | Simplifies building robust REST APIs with authentication, serialization, and permission handling. |
| **GraphQL** | Provides a flexible query language for APIs, allowing clients to request only the data they need. |
| **PostgreSQL** | A powerful open-source relational database for storing listings, users, bookings, and transactions. |
| **SQLite** | Used locally during development for fast setup and testing before moving to PostgreSQL in production. |
| **HTML5 / CSS3 / JavaScript (ES6+)** | Core technologies for building and styling the frontend user interface. |
| **React.js** | A JavaScript library for building reusable, dynamic, and interactive UI components. |
| **Bootstrap / Tailwind CSS** | Utility-first CSS frameworks to create responsive, modern designs quickly. |
| **Redis** | In-memory data store used for caching and improving performance (e.g., search, session storage). |
| **Celery** | Handles background jobs and asynchronous tasks such as sending emails and notifications. |
| **Docker** | Provides containerization for consistent development and deployment environments. |
| **NGINX** | A high-performance web server acting as a reverse proxy and load balancer for handling client requests. |
| **Gunicorn** | Python WSGI HTTP server used to serve the Django application in production. |
| **Git & GitHub** | Version control system for tracking code changes and enabling collaboration. |
| **Postman** | API testing tool for verifying endpoints and ensuring API reliability. |
---
## 🗄️ Database Design

The database is designed to handle core Airbnb-like functionality, focusing on scalability and relationships between entities.  

### Key Entities and Fields  

1. **Users**  
   - `id` (Primary Key)  
   - `name`  
   - `email` (unique)  
   - `password_hash`  
   - `role` (guest, host, admin)  

   **Notes:** A user can act as both a guest and a host.  

---

2. **Properties**  
   - `id` (Primary Key)  
   - `user_id` (Foreign Key → Users)  
   - `title`  
   - `description`  
   - `location`  
   - `price_per_night`  

   **Notes:** Each property is owned by a user (host).  

---

3. **Bookings**  
   - `id` (Primary Key)  
   - `user_id` (Foreign Key → Users)  
   - `property_id` (Foreign Key → Properties)  
   - `check_in_date`  
   - `check_out_date`  
   - `status` (pending, confirmed, cancelled)  

   **Notes:** A booking belongs to one property and is made by one user (guest).  

---

4. **Reviews**  
   - `id` (Primary Key)  
   - `user_id` (Foreign Key → Users)  
   - `property_id` (Foreign Key → Properties)  
   - `rating` (1–5)  
   - `comment`  

   **Notes:** A user can leave multiple reviews, but only one per property per booking.  

---

5. **Payments**  
   - `id` (Primary Key)  
   - `booking_id` (Foreign Key → Bookings)  
   - `amount`  
   - `payment_method` (credit card, PayPal, etc.)  
   - `status` (pending, completed, failed)  

   **Notes:** Each payment is tied to a booking.  

---

### Entity Relationships  

- A **User** can host multiple **Properties**.  
- A **User** can make multiple **Bookings**.  
- A **Property** can have many **Bookings**.  
- A **Booking** generates exactly one **Payment**.  
- A **Property** can have many **Reviews**, each written by a **User**.  

This structure ensures flexibility while keeping data consistent across users, hosts, bookings, and payments.
---
## ✨ Feature Breakdown

The Airbnb Clone project is built around core features that replicate essential Airbnb functionality. Each feature plays a role in ensuring smooth interaction between guests and hosts.  

### 1. User Management  
Allows users to sign up, log in, and manage their profiles securely. Roles (guest, host, admin) determine access and functionality, ensuring a personalized experience.  

### 2. Property Management  
Hosts can list properties by adding details such as title, description, location, price, and images. This feature enables property owners to attract potential guests and manage their listings.  

### 3. Booking System  
Guests can search, select, and book available properties for specific dates. The system ensures availability, prevents double-booking, and handles booking statuses like pending, confirmed, or cancelled.  

### 4. Reviews and Ratings  
Guests can leave reviews and ratings for properties they’ve stayed at. This feature builds trust in the platform by allowing users to make informed decisions based on feedback.  

### 5. Payments  
Supports secure payment processing tied to bookings. This ensures smooth transactions between guests and hosts, with support for multiple payment methods and statuses.  

### 6. Search and Filtering  
Users can search for properties by location, price, availability, and other criteria. This makes it easy to discover suitable properties quickly.  

### 7. Admin Dashboard  
Admins oversee the platform by managing users, properties, and bookings. This ensures quality control, security, and the smooth operation of the system.  
