# Requirement Analysis in Software Developmen
This repository explain the concept of Requirement Analysis in Software Developomment, its importance in software Development Life Cycle (SDLC), key activities involved, and how it applies to a booking management system. it also includes examples, diagraims, and acceptance criteria to demostrate practical understanding. 

## What is Requirement Analysis?
Requirement Analysis is a critical phase in the Software Development Life Cycle (SDLC) where the needs, expectations, and constraints of stakeholders are identified, analyzed, documented, and validated. It ensure that the development team fully understands what the system should do and how it should perform before design and implementation begin.
Requirement Analysis bridges the communication gap between stakeholders and developers, helping to define clear, measurable, and verifiable requirements that guide the entire project. A well-executed requirement analysis helps reduce misunderstandings, prevents rework, and ensures the final product aligns with business objectives.

## Why is Requiremment Analysis Important?
Requirement Analysis is important because:
    - Clarity and Understanding
    - Scope Definitions
    - Basis for Design and Development 
    - Cost and Time Estimations
    - Ensures Quality and User Satisfaction
    - Prevents Misunderstandings and Miscommunication

## Key Activities in Requirement Analysis
The key activities involoved in Requrement Analysis include:
- Requirement Gathering

    Collecting information from stakeholders using interviews, surveys, workshops, and observation.

- Requirement Elicitation

    Understanding and extracting actual needs, expectations, and constraints from stakeholders.

- Requirement Documentation

    Clearly recording requirements in structured formats such as SRS (Software Requirement Specification).

- Requirement Analysis and Modeling

    Analyzing collected requirements, identifying conflicts, prioritizing them, and representing them using models like diagrams and workflows.

- Requirement Validation

    Ensuring documented requirements are correct, complete, consistent, feasible, and aligned with business objectives.


## Types of Requirements
Functional Requirements: Functional requirement decribe what the system should do - the specific behaviours, services, and functionas the functions the system must support.

For the Booking Management System, examples include:

- Users should be able to create an account and log in.

- Users should be able to search for available rooms or services.

- Users should be able to book a room or service.

- Users should be able to make payments.

- Admin should manage bookings, users, and resources.


Non-Functional Requirements

Non-functional requirements describe how the system should perform. They define quality attributes, constraints, and system properties.

For the Booking Management System, examples include:

- The system should load booking search results within 3 seconds. (Performance)

- The platform should be available 99.9% of the time. (Reliability)

- User data must be encrypted and protected. (Security)

- The interface should be responsive across devices. (Usability)

- The system should support up to 10,000 concurrent users. (Scalability)


## Use Case Diagrams 

Use Case Diagrams visually represent interactions between users (actors) and the system. They help in understanding system functionality, user roles, and major processes. They are beneficial in clarifying system boundaries, identifying required features, and improving stakeholder communication.

### Actors

- User
- Admin
- Payment Gateway

### Example Use Cases

- Register/Login
- Search Booking
- Make Booking
- Make Payment
- Manage Bookings (Admin)
- Receive Confirmation Email

![Alx booking images](alx-booking-uc.png)


## Acceptance  Criteria 

Acceptance Criteria define the conditions that a feature must satisfy to be accepted as complete. They ensure requirements are testable, clear, and aligned with expected outcomes. Acceptance Criteria help developers understand expectations and help testers verify functionality.

### Example: Checkout Feature Acceptance Criteria

Checkout Feature Acceptance Criteria:

- User must be logged in to access checkout.

- System should display booking summary before payment.

- User should be able to select a payment method.

- Payment must be processed securely.

- User should receive a confirmation message after successful payment.

- A confirmation email or receipt should be sent automatically.

- Booking status must update to “Confirmed” after payment.

- If payment fails, an appropriate error message should appear.