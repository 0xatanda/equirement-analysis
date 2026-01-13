# Requirement Analysis in Software Development

This repository explains the concept of Requirement Analysis in software development, its role in the Software Development Life Cycle (SDLC), and how it applies to a booking management system. It includes examples, diagrams, and acceptance criteria to demonstrate practical understanding.

## Table of Contents

- [What is Requirement Analysis?](#what-is-requirement-analysis)
- [Why Requirement Analysis Matters](#why-requirement-analysis-matters)
- [Key Activities](#key-activities)
- [Types of Requirements](#types-of-requirements)
  - [Functional Requirements](#functional-requirements)
  - [Non-Functional Requirements](#non-functional-requirements)
- [Use Case Diagram](#use-case-diagram)
- [Acceptance Criteria](#acceptance-criteria)

## What is Requirement Analysis?

Requirement analysis is the phase of the SDLC where stakeholders' needs, expectations, and constraints are identified, analyzed, documented, and validated. It ensures the development team understands what the system should do and how it should perform before design and implementation begin.

Good requirement analysis bridges the communication gap between stakeholders and developers, producing clear, measurable, and verifiable requirements that guide the project and reduce rework.

## Why Requirement Analysis Matters

- **Clarity:** Defines what success looks like for stakeholders and the team.
- **Scope control:** Prevents scope creep by documenting agreed requirements.
- **Basis for design:** Guides architecture and implementation decisions.
- **Estimations:** Improves accuracy of cost and time estimates.
- **Quality & satisfaction:** Helps deliver a product aligned with user needs.

## Key Activities

- **Requirement Gathering:** Collect data from stakeholders via interviews, surveys, workshops, and observation.
- **Requirement Elicitation:** Probe stakeholders to discover real needs, not just requests.
- **Requirement Documentation:** Record requirements in structured artifacts such as an SRS (Software Requirements Specification).
- **Requirement Analysis & Modeling:** Identify conflicts, prioritize requirements, and create models (e.g., workflows, diagrams).
- **Requirement Validation:** Verify requirements are correct, complete, feasible, and testable.

## Types of Requirements

### Functional Requirements

Functional requirements describe what the system should do. For a Booking Management System, examples include:

- Users can create an account and log in.
- Users can search for available rooms or services.
- Users can make a booking.
- Users can complete payments.
- Administrators can manage bookings, users, and resources.

### Non-Functional Requirements

Non-functional requirements describe how the system should perform (quality attributes and constraints). Example requirements:

- The system should return search results within 3 seconds (Performance).
- The platform should be available 99.9% of the time (Reliability).
- User data must be encrypted at rest and in transit (Security).
- The interface must be responsive across devices (Usability).
- The system should support up to 10,000 concurrent users (Scalability).

## Use Case Diagram

Use case diagrams show interactions between actors and the system, clarifying system boundaries and major processes.

**Actors**

- User
- Admin
- Payment Gateway

**Example Use Cases**

- Register / Login
- Search Booking
- Make Booking
- Make Payment
- Manage Bookings (Admin)
- Receive Confirmation Email

![Use-case diagram for booking system](alx-booking-uc.png)

## Acceptance Criteria

Acceptance criteria define the conditions a feature must meet to be considered complete and testable.

### Example: Checkout — Acceptance Criteria

- User must be authenticated to access checkout.
- Booking summary is displayed before payment is initiated.
- User can select among available payment methods.
- Payment is processed securely and confirmed to the user.
- A visible confirmation message is shown after successful payment.
- A confirmation email or receipt is sent automatically.
- Booking status updates to "Confirmed" after payment succeeds.
- If payment fails, an appropriate error message is shown and booking remains pending.

---

If you'd like, I can also:

- Add an example SRS section.
- Provide a sample acceptance test checklist or BDD-style scenarios.
- Generate a cleaned SVG/PNG use-case diagram and place it in the repo.

Feel free to tell me which of these you'd like next.