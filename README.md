# Requirement Analysis in Software Development
The purpose of this stage is to gather, clarify, and document the functional and non-functional requirements of the software so that developers, designers, and stakeholders have a clear, shared vision. This process helps prevent misunderstandings, reduces costly rework, scope creep and ensures that the final product solves the right problem effectively.

# What is Requirement Analysis?
Requirement Analysis is the process of identifying, gathering, analyzing, and documenting the needs and expectations of users and stakeholders for a software system. It is a critical phase in the Software Development Life Cycle (SDLC) because it lays the foundation for designing, building, testing, and deploying a product that meets user needs and business goals.

## 🧩 What Does Requirement Analysis Involve?
### Gathering Requirements
    – Interviewing stakeholders
    – Distributing questionnaires
    – Observing user environments
    – Reviewing existing systems

### Analyzing Requirements
    – Ensuring requirements are complete, consistent, and realistic
    – Identifying potential risks, gaps, or conflicts
    – Prioritizing features and constraints

### Documenting Requirements
    – Creating clear and formal documentation like SRS (Software Requirements Specification)
    – Including both functional (what the system should do) and non-functional (performance, security, usability) requirements

### Validating and Reviewing
    – Getting stakeholder sign-off
    – Using models like use case diagrams, user stories, or wireframes to validate understanding

# Why is Requirement Analysis Important?
### ✅ 1. Ensures Project Clarity and Direction
It defines what is to be built and aligns the development team with the client’s vision.
### ✅ 2. Reduces Risks and Costly Rework
Clear requirements prevent misunderstandings and reduce the chances of developing incorrect or incomplete features.
### ✅ 3. Improves Time and Resource Management
With well-defined requirements, project managers can better estimate timelines, costs, and allocate resources efficiently.
### ✅ 4. Supports Better Design and Development
Requirements serve as the blueprint that developers and designers follow throughout the SDLC.
### ✅ 5. Enhances Communication
It creates a common language between technical teams and non-technical stakeholders, ensuring everyone is on the same page.

## 🌀 Role of Requirement Analysis in the SDLC Stages
| SDLC Stage  | Role of Requirement Analysis                              |
| ----------- | --------------------------------------------------------- |
| Planning    | Defines scope and feasibility of the project              |
| Design      | Provides input for system architecture and UI/UX design   |
| Development | Guides developers on what features to build               |
| Testing     | Helps QA teams create test cases to validate requirements |
| Deployment  | Ensures the final product meets the intended purpose      |
| Maintenance | Identifies additional requirements for future updates     |

# Key Activities in Requirement Analysis.
## 📌 1. Requirement Gathering
        • Involves collecting initial information about the desired system from stakeholders.
        • Focuses on what the users need, not how the system will work.
        • Techniques include interviews, questionnaires, observations, and reviewing existing documents.
        • Key stakeholders: clients, end-users, business analysts, and product owners.
        • Goal: Build a high-level understanding of the project scope and user expectations.

## 📌 2. Requirement Elicitation
        • The process of actively extracting and clarifying requirements from stakeholders.
        • Goes deeper than gathering by asking follow-up questions, resolving ambiguities, and identifying hidden needs.
        • Techniques: brainstorming sessions, use case development, workshops, prototyping, role-playing.
        • Encourages open communication to avoid assumptions.
        • Goal: Discover both explicit and implicit requirements.

## 📌 3. Requirement Documentation
        • Converts gathered and elicited requirements into a structured, written format.
        • Often done through a Software Requirements Specification (SRS) document.
        • Includes functional (what the system does) and non-functional (performance, security, scalability) requirements.
        • Should be clear, complete, unambiguous, and testable.
        • Serves as a contract between stakeholders and developers.

## 📌 4. Requirement Analysis and Modeling
        • Involves evaluating and organizing requirements to ensure they are feasible, complete, and consistent.
        • Helps identify conflicts, overlaps, or gaps in the requirements.
        • Modeling tools include:
        • Use case diagrams
        • Data flow diagrams (DFDs)
        • Entity-relationship diagrams (ERDs)
        • Wireframes or mockups
        • Goal: Translate raw requirements into structured logic and models to guide design and development.

## 📌 5. Requirement Validation
        • Ensures the documented and modeled requirements are accurate and truly reflect stakeholder needs.
        • Conducted through reviews, walkthroughs, and validation meetings.
        • Involves both technical teams and stakeholders.
        • Checks for correctness, completeness, consistency, and feasibility.
        • Goal: Get formal approval from stakeholders before moving to the design and development phase.

# Types of Requirements.
## Functional Requirements
### 1.	User Authentication & Role Management
        • Users must be able to register, log in, and manage their profiles.
        • Support role-based access (e.g., Guest, Hotel Manager, Admin) 
### 2.	Hotel & Room Listings Management
        • Hotel managers can add/update/delete hotel properties, room types, pricing, photos, and descriptions 
        • Display room details with availability for users.
### 3.	Search & Filter Catalog
        • Users can search for available rooms by destination, check-in/check-out dates, and apply filters like price, 
          amenities, and hotel ratings 
### 4.	Booking Placement & Management
        • Users should be able to select rooms, set dates, and complete bookings via an interactive booking flow 
        • Users can view, modify, or cancel their bookings and receive confirmations.
### 5.	Payment Integration & Confirmation
        • Integrate secure payment gateways for payment processing.
        • After payment, users receive confirmations, and booking and payment are recorded reliably 
### 6.	Notification System
        • Send real-time notifications (e.g., booking confirmation, reminders) to users and hotel managers upon relevant actions 

## Non-Functional Requirements
### 1.	Performance & Latency
        • System must quickly return search results and booking operations—ideally within 500ms 
        • High read/write performance during peak times .
### 2.	Scalability & Availability
        • Handle high user traffic and booking volumes, supporting auto-scaling during peak times .
        • Aim for >99.99% uptime .
### 3.	Consistency & Reliability
        • Ensure no double-bookings (strong consistency for availability checks) 
        • Robust fault tolerance and reliable data replication 
### 4.	Usability & Accessibility
        • Interface should be intuitive, mobile-friendly, and accessible to users with disabilities (WCAG standards) 
### 5.	Security
        • Encrypt sensitive data (personal information, payments) and implement secure authentication and authorization 
        • Comply with PCI-DSS standards for payment handling.

# Use Case Diagrams.
## What Are Use Case Diagrams?
A Use Case Diagram is a visual modeling tool used in software engineering to describe the interactions between users (actors) and a system. 
It shows what the system should do — not how it does it — by representing different use cases (functions or features) that the system offers.
Use case diagrams are part of the Unified Modeling Language (UML) and are commonly used during the requirement analysis and design phases 
of the Software Development Life Cycle (SDLC).

## Key Components of a Use Case Diagram
| Element           | Description                                                                      |
| ----------------- | -------------------------------------------------------------------------------- |
| **Actor**         | A user or external system that interacts with the system (e.g., Customer, Admin) |
| **System**        | The software or platform being modeled                                           |
| **Use Case**      | A task or function the actor can perform (e.g., "Book Room", "Login")            |
| **Relationships** | Lines connecting actors to use cases, showing interactions                       |

https://github.com/mikenbze/requirement-analysis/blob/main/alx-booking-uc.png

# Acceptance Criteria.
## Importance of Acceptance Criteria in Requirement Analysis
Acceptance Criteria are the conditions that a software product must meet for a feature or requirement to be accepted by the client or end-user. They define “done” in clear, testable terms. In Requirement Analysis, acceptance criteria play a critical role by:
✅ Ensuring clarity: They remove ambiguity by clearly stating what must happen for a feature to be considered complete.
✅ Guiding development: Developers understand exactly what functionality they need to build.
✅ Supporting testing: Testers can write precise test cases based on defined outcomes.
✅ Facilitating collaboration: They align stakeholders (business, developers, QA) with a shared understanding of expectations.
✅ Reducing rework: By defining what success looks like up front, teams avoid costly revisions later.

## 🧾 Example: Acceptance Criteria for the Checkout Feature in a Booking Management System
## Feature: Checkout Process
## User Story:
    ### As a guest, I want to securely complete my booking and receive confirmation after payment, so that I know my reservation is successful.
## Acceptance Criteria:
    ✅ The user must be logged in to access the checkout page.
    ✅ The checkout page displays booking summary (hotel, room type, dates, price).
    ✅ The user can enter and save billing information securely.
    ✅ The system supports at least two payment options (e.g., credit card and mobile money).
    ✅ Payment gateway integration must securely process the transaction.
    ✅ Upon successful payment, the system displays a confirmation message and booking reference.
    ✅ The system sends a confirmation email or SMS to the user.
    ✅ The booking status in the database updates to "Confirmed".
    ✅ If payment fails, an error message is displayed with retry instructions.
