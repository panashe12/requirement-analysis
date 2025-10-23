# requirement-analysis
Requirement Analysis in Software Development.


INTRODUCTION
 # 🧩 Requirement Analysis in Software Development

Welcome to the REQUIREMENT ANALYSIS repository!

This repository has been created to document and demonstrate the process of REQUIREMENT ANALYSIS in the context of software development specifically through the example of building an Airbnb Clone Application.

The purpose of this repository is to outline how project requirements are identified, analyzed, and structured before the design and development stages begin. It serves as a learning resource to understand the importance of clear and well-defined requirements in delivering successful software products.



**What is Requirement Analysis?**

Requirement Analysis is a critical phase in the Software Development Life Cycle (SDLC) where the needs and expectations of end-users and stakeholders are gathered, analyzed, and documented.  

It involves defining what the software should do and how it should perform, ensuring that all stakeholders have a clear understanding of the project’s objectives before development begins.

During this phase, software engineers, project managers, and clients collaborate to identify the functional (what the system should do) and non-functional (how the system should perform) requirements of the project.  

**Why is Requirement Analysis Important?**

1. Clarity of Objectives: Helps ensure that developers and clients share a common understanding of the software’s goals.  
2. Reduces Development Errors: By identifying requirements early, potential issues or misunderstandings can be addressed before coding starts.  
3. Efficient Resource Management: Clear requirements help in estimating time, cost, and resources accurately.  
4. Improves Quality Assurance: Well-defined requirements make it easier to test and validate that the final product meets user expectations.  
5. Supports Better Design Decisions:A detailed analysis provides a foundation for creating scalable, user-friendly, and maintainable systems.

In short, requirement analysis acts as the blueprint of the software project guiding every stage from design and implementation to testing and deployment.



**KEY ACTIVITIES IN REQUIREMENT ANALYSIS**


The Requirement Analysis process involves several key activities that ensure all software requirements are accurately identified, understood, and validated before development begins.  

Below are the five main activities involved:

Requirement Gathering
- Collecting information from stakeholders, users, and clients to understand their needs and expectations.  
- Using methods like interviews, surveys, observations, and brainstorming sessions.  
- Ensures that all necessary data about the system’s functionality and constraints are obtained.

Requirement Elicitation
- Refining gathered information to clearly define the user’s actual needs.  
- Involves engaging stakeholders to uncover hidden or unclear requirements.  
- Helps bridge the communication gap between users and developers.

Requirement Documentation
- Organizing and recording all requirements in a structured format such as a Software Requirement Specification (SRS) document.  
- Provides a formal reference that guides the design, development, and testing teams.  
- Ensures that no requirement is missed or misunderstood.

Requirement Analysis and Modeling
- Analyzing requirements to identify conflicts, redundancies, and feasibility.  
- Using tools and models (like use case diagrams, flowcharts, and data models) to represent system behavior and structure.  
- Helps developers and stakeholders visualize the system before implementation.

Requirement Validation
- Reviewing the documented requirements with stakeholders to confirm accuracy and completeness.  
- Ensures that each requirement aligns with the business objectives and user expectations.  
- Detects and corrects any inconsistencies early in the development cycle.


Together, these activities ensure that the software project is built on a clear, validated, and comprehensive understanding of user needs, reducing errors and improving overall project success.


**Types of Requirements**

  In the context of the hotel booking system, requirements are categorized into two main types: Functional Requirements and Non-Functional Requirements. Below are the definitions and examples for each:



  Functional Requirements

  Functional requirements define the specific behaviors, features, and interactions that the system must support. These requirements describe **what the system should do** to fulfill user needs and business objectives.

  Examples

- Hotel Management Service:  
  - Hotel managers can register and manage hotel details, including room types, pricing, and availability.  
  - Managers can update room information and monitor booking statuses.  
  - The system supports CRUD (Create, Read, Update, Delete) operations for room data.  
  - Managers receive notifications for new bookings and cancellations.

- Customer Service (Search + Booking):  
  - Customers can search for hotels based on location, dates, and amenities.  
  - The system displays available rooms with real-time pricing and availability.  
  - Customers can book rooms and receive instant booking confirmations.  
  - The platform supports multiple payment methods and processes transactions securely.

- View Booking Service:  
  - Users can view their current and past bookings.  
  - The system allows users to modify or cancel existing reservations.  
  - Booking details, including payment status and check-in/check-out times, are accessible.


 Non-Functional Requirements

Non-functional requirements specify the **quality attributes** and constraints of the system. They define **how** the system performs its functions and ensure the system meets certain standards of performance, reliability, and usability.

Examples:

- Performance:  
  - The system should handle a high volume of concurrent users without significant degradation in response time.  
  - Search queries should return results within 2 seconds.

- Scalability:  
  - The architecture must support horizontal scaling to accommodate increased user load.  
  - The system should efficiently manage a growing number of hotel listings and bookings.

- **Availability**:  
  - The system should be available 99.9% of the time, with minimal downtime for maintenance.  
  - Failover mechanisms should be in place to ensure continuous service during outages.

- **Security**:  
  - User data, including personal and payment information, must be encrypted and stored securely.  
  - The system should comply with relevant data protection regulations (e.g., GDPR, PCI-DSS).

- **Usability**:  
  - The user interface should be intuitive and accessible across various devices.  
  - Users should be able to complete booking processes with minimal steps and clear guidance.


These requirements collectively ensure that the hotel booking system is functional, reliable, and user-friendly, meeting both user expectations and business goals.


##  Use Case Diagrams

**Use Case Diagrams** are a type of UML (Unified Modeling Language) diagram that visually represents the interactions between users (actors) and a system. They help illustrate **who uses the system** and **what functionalities the system provides**.  

### 🔹 Benefits of Use Case Diagrams
- Provides a high-level overview of system functionality.  
- Helps communicate requirements to stakeholders clearly.  
- Identifies all actors and interactions, reducing the chance of missing features.  
- Serves as a foundation for further system design and development.  

### 🔹 Actors in the Booking System
- **Guest / Customer**: Searches for hotels, makes bookings, cancels or modifies reservations, leaves reviews.  
- **Hotel Manager / Host**: Manages hotel listings, updates room availability, monitors bookings.  
- **Payment Service**: Processes customer payments securely.  
- **System Administrator**: Oversees the platform, manages user accounts, and ensures system integrity.  

### 🔹 Use Cases
- Search Hotels  
- Filter Hotels by Price, Location, Amenities  
- View Hotel Details  
- Make Booking  
- Cancel or Modify Booking  
- Leave Review and Rating  
- Manage Hotel Listing  
- Process Payment  
- Generate Booking Reports  


### 🔹 Use Case Diagram
Below is the use case diagram for the booking system:

![<img width="1024" height="1024" alt="alx-booking-uc" src="https://github.com/user-attachments/assets/add1cb7d-6650-4b43-830a-1e602104e2b2" />](alx-booking-uc.png)
<img width="1024" height="1024" alt="alx-booking-uc.png" src="https://github.com/user-attachments/assets/add1cb7d-6650-4b43-830a-1e602104e2b2" />

> **Note:** The diagram was created using tools like **Draw.io** and exported as `alx-booking-uc.png`. It visually represents the actors and their interactions with the booking system.


