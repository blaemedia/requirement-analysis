# Requirement Analysis in Software Development

This repository explores the concept of **Requirement Analysis** — a crucial phase in the Software Development Life Cycle (SDLC).  
It provides explanations, examples, and visual documentation that demonstrate how to identify, analyze, and validate system requirements before development begins.

## What is Requirement Analysis?

**Requirement Analysis** is the process of identifying, documenting, and managing the needs and expectations of stakeholders for a new or modified software system.  
It serves as the foundation for the entire software development process by clearly defining what the system should do and how it should perform.

During this stage, analysts interact with clients, end users, and developers to gather information about business goals, constraints, and desired functionalities.

Requirement Analysis ensures:
- A clear understanding between stakeholders and developers.
- Reduced chances of rework and project failure.
- Efficient resource planning and implementation.

In the **Software Development Life Cycle (SDLC)**, this stage typically follows feasibility study and precedes design and implementation.

## Why is Requirement Analysis Important?

Requirement Analysis is essential in ensuring a project’s success. Some key reasons include:

1. **Prevents Miscommunication:**  
   It bridges the gap between stakeholders and developers by clearly defining expectations and deliverables.

2. **Saves Time and Cost:**  
   Detecting requirement issues early reduces redesign, redevelopment, and testing costs later in the project.

3. **Improves Quality:**  
   Well-analyzed requirements ensure that the final product meets both functional and business goals, improving user satisfaction.

## Key Activities in Requirement Analysis

1. **Requirement Gathering:**  
   Collecting raw data about business needs through interviews, surveys, and observation.

2. **Requirement Elicitation:**  
   Engaging with stakeholders to refine and clarify the gathered information.

3. **Requirement Documentation:**  
   Structuring and writing the requirements in clear, standardized formats.

4. **Requirement Analysis and Modeling:**  
   Analyzing requirements for feasibility, consistency, and completeness, and representing them through models or diagrams.

5. **Requirement Validation:**  
   Ensuring that documented requirements truly represent stakeholder needs before proceeding to design.

   ## Types of Requirements

### 1. Functional Requirements
These describe **what the system should do** — the core operations, features, or services.

**Examples (Booking Management System):**
- Users should be able to **search** available rooms based on date and location.
- The system should allow **booking confirmation** after payment.
- Admins should be able to **add, edit, or delete listings**.
- The system should **send email notifications** upon successful booking.

### 2. Non-functional Requirements
These define **how the system should perform** rather than what it does.

**Examples (Booking Management System):**
- The website should load within **3 seconds**.
- The system should handle up to **500 concurrent users**.
- Data should be **encrypted** during payment transactions.
- The platform should be **responsive** on both web and mobile devices.

## Use Case Diagrams

A **Use Case Diagram** visually represents interactions between **actors** (users or systems) and the **use cases** (functions) they perform.  
They help developers and stakeholders understand the system’s scope and user interactions.

**Benefits:**
- Clarifies system functionality.
- Helps identify actors and their relationships with system processes.
- Simplifies requirement validation and communication.

### Example — Booking Management System

Actors:
- Guest (User)
- Admin
- Payment Gateway

Use Cases:
- Search Rooms
- Make Booking
- Process Payment
- Manage Listings
- Send Notifications

! [Use Case Diagram] alx-booking-uc.png



## Acceptance Criteria

**Acceptance Criteria** define the conditions that a software feature must meet to be accepted by stakeholders.  
They act as a **checklist** for developers and testers to verify that the system behaves as expected.

**Importance:**
- Ensures all requirements are testable and measurable.  
- Prevents ambiguity in defining “done.”  
- Provides a shared understanding among the team.

**Example (Checkout Feature):**

| Criteria | Description |
|-----------|--------------|
| **AC1** | User must be able to review booking details before payment. |
| **AC2** | Payment process must use a secure gateway (e.g., Paystack or Stripe). |
| **AC3** | A confirmation email must be sent after successful payment. |
| **AC4** | System should update booking status to “Confirmed.” |
| **AC5** | User should be redirected to the “Booking Summary” page post-checkout. |


