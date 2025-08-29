# requirements-analysis
This repo is a documentation to show what a Requirements Analysis document is and how it plays a key role in the SDLC.

## What is Requirement Analysis?
Requirement Analysis is the process of identifying, gathering, analyzing, and documenting the needs and expectations of stakeholders for a software project. It is one of the most crucial phases of the Software Development Life Cycle (SDLC) because it lays the foundation upon which the entire system is designed and built.

## Why is Requirement Analysis Important?
1. Clarity of Scope – Prevents misunderstandings by ensuring all stakeholders have a common understanding of the system.
2. Prevents Rework – Early identification of needs reduces costly changes later in development.
3. Guides Design & Development – Provides a blueprint for system architecture, coding, and testing.
4. Improves Quality – Clear requirements ensure the final product meets user expectations and business objectives.
5. Enhances Communication – Acts as a bridge between stakeholders and developers by translating business needs into technical terms.
6. Facilitates Testing – Test cases are designed based on documented requirements, ensuring complete coverage.
7. Risk Reduction – Identifies potential issues, constraints, or conflicts at an early stage.

## Key Activities in Requirement Analysis
* Requirement Gathering – Collecting input from stakeholders (clients, users, business analysts, managers, etc.) through interviews, questionnaires, workshops, and observation.
* Requirement Elicitation – Clarifying and uncovering hidden requirements using techniques like brainstorming, prototyping, and workshops.
* Requirement Documentation – Preparing structured records such as the Software Requirement Specification (SRS) to capture functional and non-functional needs.
* Requirement Analysis and Modeling – Examining requirements for feasibility, consistency, and completeness, often using diagrams and models like UML or DFDs.
* Requirement Validation – Ensuring requirements are correct, complete, realistic, and aligned with business goals through reviews, walkthroughs, and prototypes.

## Types of Requirements
### Functional Requirements  
Functional requirements define what the system should do. They describe the specific features, services, and interactions that the system must provide to meet user and business needs.

**Examples for Booking Management Project:**  
- User registration and login for customers and hotel managers  
- Search functionality for hotels based on location, price, ratings, or availability  
- Hotel managers adding, updating, or removing hotel listings  
- Customers booking hotels with real-time availability checking  
- Secure payment processing using third-party payment gateways  
- Viewing and managing past and upcoming bookings  
- Sending booking confirmation and cancellation notifications to users and managers  

### Non-functional Requirements  
Non-functional requirements define how the system should perform rather than what it should do. They set the quality standards, constraints, and performance benchmarks for the system.

**Examples for Booking Management Project:**  
- High scalability to handle thousands of users and bookings simultaneously  
- Fast response time (search and booking results should load within 2–3 seconds)  
- 99.9% system uptime to ensure continuous availability  
- Data security with encryption for user information and payments  
- Mobile responsiveness for seamless use on phones, tablets, and desktops  
- Integration with CDN for faster content delivery worldwide  
- Logging, monitoring, and error handling for system reliability

## Use Case Diagrams

### What are Use Case Diagrams?
Use Case Diagrams are a type of Unified Modeling Language (UML) diagram that visually represent the functional requirements of a system. They show **how different users (actors)** interact with the system and what **use cases (functions)** they can perform.  

### Benefits of Use Case Diagrams
- Provide a clear picture of system functionality from the user’s perspective  
- Help identify all possible interactions between users and the system  
- Bridge communication between stakeholders, developers, and testers  
- Serve as a foundation for writing detailed use case scenarios  

### Use Case Diagram for Booking System
The main actors in the booking system are:  
- **Customer** (searches hotels, makes bookings, payments, views bookings)  
- **Hotel Manager** (manages hotel listings, views bookings, receives notifications)  
- **Payment Gateway** (processes secure payments)  
- **System Administrator** (manages users, monitors system performance)  

**Main Use Cases include:**  
- Register/Login  
- Search Hotels  
- Book Hotel  
- Make Payment  
- Cancel Booking  
- View Bookings  
- Manage Hotel Listings  
- Receive Notifications  
- Manage Users  

### Diagram
<img width="578" height="337" alt="alx-booking-uc.png" src="https://github.com/user-attachments/assets/e9fb59e5-68da-4cba-8739-52bf397f8645" />

## Acceptance Criteria

### Importance of Acceptance Criteria in Requirement Analysis
Acceptance Criteria are the predefined conditions that a software product must meet to be accepted by stakeholders, clients, or end-users. They play a crucial role in Requirement Analysis by:  
- Ensuring that all requirements are measurable and testable  
- Providing clarity to developers on what needs to be built  
- Reducing ambiguity by clearly defining the scope of a feature  
- Acting as a reference point for quality assurance and testing  
- Aligning stakeholders and development teams on expected outcomes  

### Example: Checkout Feature in Booking Management System
**Acceptance Criteria for Checkout:**  
1. The system must allow users to view all selected bookings before proceeding to checkout.  
2. The system must display the total price, including taxes and fees, before payment.  
3. The user must be able to choose a payment method (e.g., credit card, PayPal, mobile money).  
4. The system must validate payment details before processing.  
5. A confirmation message must be shown after successful payment.  
6. The system must send a booking confirmation email to the user within 5 minutes of checkout.  
7. If payment fails, the system must display an error message and allow the user to retry.  
