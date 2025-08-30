# requirement-analysis

What is Requirement Analysis?
Requirement analysis is the critical phase in software developmemt lifecycle where project team gathers, analyzes and defines the requirements of the software product to be developed.

Why is Requirement Analysis Important?
1. Clarity and understanding: it helps in understanding what the stakeholders expect from the software, reducing ambiguity.
2. Scope Definition: clearly defines the scope of the project, which helps in preventing scope creep
3. Cost and Time Estimation: Facilitates accurate estimztion of project cost, resources, and time

Key Activities in Requirement Analysis
1. Requirement Gathering: Engage with stakeholders to collect initial requirements, using various techniques like interviews, surveys and workshops
2. Requirement Elicitation:Refine and elaborate on the gathered requirements, using techniques like brainstorming, focus groups and prototyping.
3. Requirement Documentation:Document the requirement in a detailed and structured format, use requirement specification documents, user stories, and use cases
4. Requirement Analysis and Modeling: Analyze and prioritize the requirements. create models to visualize and understand requirements
5. Requirement Validation: Review and validate thhe requirements with the stakeholders.

Types of Requirements
1. Functional Requirements: Describe what the system should do.
   examples; customer service, view booking sefrvice
2. Non-Functional Requirements: Describe how the syatem should perform
   examples; Hotel management service

Use Case Diagrams
Use case diagrams show how different users(actors) interacy with the system to achieve specific goals(use ccases)

Benefit of use case diagrams
1. Provide a clear visual representation of system functionalities
2. Help in identifying and organizing system requirements
3. Facilitate communication among stakeholders and development team
<img width="681" height="761" alt="alx-booking-uc.png" src="https://github.com/user-attachments/assets/40f649ae-3fa9-4786-b1e8-ad66ff41699d" />


Acceptance Criteria
conditions that a feature must meet to be accepted by the stakeholders

Acceptance Criteria for Checkout Feature
Successful Checkout
   1. Given a guest has an active booking,
   2. When the receptionist clicks “Checkout” for that booking,
   3. Then the system should mark the booking status as “Checked Out”
   4. And release the room for future bookings.
 Bill Settlement Requirement
   1. Given a guest has pending charges,
   2. When checkout is initiated,
   3. Then the system must prompt for full payment of outstanding charges
   4. And prevent checkout until the payment is settled.
Invoice Generation
   1. Given a checkout is successfully completed,
   2. When the booking is closed,
   3. Then the system should generate a final invoice (including room                charges, taxes, and additional services)
   4. And email or print it for the guest.
Late Checkout Handling
   1. Given a guest checks out later than the scheduled time,
   2. When the checkout is processed,
   3. Then the system should automatically add a “Late Checkout Fee” (if             applicable, per business rules) to the final bill.
System Logging & Audit
   1. Given a checkout is completed,
   2. When the status is updated,
   3. Then the system should log the action with user ID, timestamp, and             booking ID for audit purposes.





