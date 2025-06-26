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
        • Users can search for available rooms by destination, check-in/check-out dates, and apply filters like price, amenities, and hotel ratings 
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
