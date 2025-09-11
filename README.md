# Web-Based Alumni Networking System

## Introduction:

A project document including the requirement analysis, problem statement, relevant software development model, and functional and non-functional requirements for a Web-Based Alumni Networking System.

---

## Functional Overview:

- Document the requirement analysis to define the system's purpose and needs.
- Outline the problem statement to identify existing gaps.
- Specify objectives to guide the project direction.
- Define scope and limitations to set project boundaries.
- Select and justify a suitable software development model.
- List functional and non-functional requirements for system development.

This document provides a comprehensive foundation for the Web-Based Alumni Networking System, ensuring all requirements are clearly documented to support subsequent design and development phases.

---

## Requirement Analysis:

#### Introduction

In the modern academic environment, maintaining strong connections with alumni has become essential for institutional development and student career support. We are planning to develop a web-based Alumni Networking System that will enable alumni to register, interact, and collaborate with their peers and institution.

The platform will serve as a central hub for alumni to stay engaged, contribute back, and build professional networks. It will also help current students benefit from mentorship, industry insights, and job referrals from graduates.

#### Problem Statement

Currently, there is no centralized system in our institution that enables alumni to connect with each other or with current students. Important alumni events and opportunities often go unnoticed due to poor communication. This leads to a disconnect between the institution and its graduates. A lack of organized platforms for networking and knowledge sharing limits the potential benefits that alumni engagement can offer. Therefore, we aim to create a structured system that brings together alumni, students, and faculty in one collaborative environment.

#### Objectives

- Develop a centralized web-based platform for alumni engagement.
- Allow users to register, create profiles, and connect with peers.
- Enable secure communication between alumni and institution.
- Provide a dashboard for event listings, job posts, and announcements.
- Create an admin interface for content and user management.
- Promote collaboration between alumni and current students.

#### Scope

- The system will support alumni registration and authentication.
- Users will be able to post and view events, jobs, and announcements.
- Messaging and connection features will allow peer communication.
- Admins will be able to manage users and content.
- The platform will support mobile responsiveness.

#### Limitations

- The initial version will be limited to alumni of our campus only.
- Delivery systems or physical meetups will not be handled.
- External social media integrations may not be included at first.
- Engagement will depend on user participation.

---

### System Analysis and Design:

#### Development Methodology

We plan to use the **Agile Software Development Methodology** for this project. Agile is suitable for web applications that require continuous improvement, testing, and feedback. It allows us to work in iterative cycles, incorporating changes based on user suggestions and real-world usage.

**Planned Phases:**

- Requirement Gathering: Collecting needs and defining key features.
- Planning: Dividing the system into modules and setting timelines.
- Design: Creating wireframes, UI prototypes, and database schemas.
- Implementation: Building the project using MERN stack.
- Testing: Performing unit, integration, and user testing to identify bugs.
- Deployment: Hosting the system on a suitable cloud provider.
- Feedback: Gathering responses from users and improving the platform.

**Functional Requirements (Planned):**

- Alumni registration and login functionality.
- Profile creation and editing.
- Messaging between alumni users.
- Event creation and joining options.
- Announcement board visible to all users.
- Admin control panel for user and content management.

**Non-Functional Requirements (Planned):**

- Performance: The system should respond quickly under standard load.
- Scalability: Must be able to support hundreds of users in future phases.
- Availability: Should maintain at least 99.9% uptime.
- Security: Data will be protected using encryption and authentication.
- Responsiveness: UI will adapt to both desktop and mobile screens.
- Maintainability: Code will be modular and well-documented.

---

## System Requirements Specification (SRS):

The primary aim is to prepare a System Requirements Specification
(SRS) document for a Web-Based Alumni Networking System, detailing the
technical, operational, and economic feasibility to ensure a robust
foundation for system design and development.

### Functional Overview

- SRS Document: Provides a detailed specification of system requirements, including feasibility analysis.
- Feasibility Analysis: Assesses the technical, operational, and economic viability of the project.
- Foundation for Design: Serves as a basis for subsequent development phases, including data flow diagrams and implementation.

---

### Feasibility Analysis

- **Technical Feasibility:** The project will use the MERN stack (MongoDB, Express.js, React.js, and Node.js) which is widely supported and familiar to the team. Tools like Postman, GitHub, and VS Code will be used during development.
- **Operational Feasibility:** The platform will meet institutional goals by improving alumni engagement and helping students through mentorship and connections.
- **Economic Feasibility:** Free-tier services like Vercel and MongoDB Atlas will minimize development costs. No licensing or infrastructure costs are expected initially.

---

## Data Flow Diagrams (DFD):

The primary aim is to design and analyze **Data Flow Diagrams (DFDs)** to represent the data flow within a Web-Based Alumni Networking System.

### Functional Overview

- **Level 0 DFD:** Provides an overview of the system.


  ![Level 0 DFD](./assets/level0.png)

- **Level 1 DFD:** Breaks down the Level 0 diagram into detailed processes.


  ![Level 1 DFD](./assets/level1.png)

- **Level 2 DFD:** Further decomposes specific processes.  

  1. **Events**


     ![Level 2 Events](./assets/level2_events.png)

  2. **Message**  


     ![Level 2 Message](./assets/level2_message.png)

  3. **Profile**  


     ![Level 2 Profile](./assets/level2_profile.png)

  4. **Register**  


     ![Level 2 Register](./assets/level2_register.png)

  5. **Users**  

  
     ![Level 2 Users](./assets/level2_users.png)
---
## Use Case, Activity, Sequence, and Class Diagrams:

### Functional Overview

- **Use Case Diagram:**  
  Illustrates interactions between actors and the system.

  ![Use Case Diagram](./assets/usecase.png)

- **Class Diagram:**  
  Defines the static structure and relationships of system entities.

  ![Class Diagram](./assets/class.png)

- **Activity Diagrams:**  
  Depict the dynamic workflows of subprocesses:

  - Register Alumni Process

    ![Register Alumni Process](./assets/activity_register.png)

  - Send Message Process

    ![Send Message Process](./assets/activity_message.png)

  - Update Profile Process

    ![Update Profile Process](./assets/activity_profile.png)

  - Manage Users Process

    ![Manage Users Process](./assets/activity_users.png)

  - Post/View Events Process

    ![Post/View Events Process](./assets/activity_events.png)  

- **Sequence Diagrams:**  
  Show the ordered interactions between actors and the system:

  - Register Alumni Process

    ![Register Alumni Process Sequence](./assets/sequence_register.png)

  - Send Message Process

    ![Send Message Process Sequence](./assets/sequence_message.png)

  - Update Profile Process

    ![Update Profile Process Sequence](./assets/sequence_profile.png)

  - Manage Users Process

    ![Manage Users Process Sequence](./assets/sequence_users.png)

  - Post/View Events Process

    ![Post/View Events Process Sequence](./assets/sequence_events.png)

- **Purpose:**  
  Enhances understanding of system design and supports development.

---
## Test Plan and Test Cases:

### Test Plan

**Test Objectives:** 
- Verify login, profile, messaging, event management, and admin actions.
- Ensure database data integrity.
- Identify and fix UI/backend bugs.
- Validate security and performance.

**Test Scope:** 
- In Scope: Registration, profile, messaging, events, admin management.
- Out of Scope: Third-party service integration, load testing 100 users.

**Test Strategy:** 
- Manual + automated testing (Selenium, Postman).
- Unit, integration, and user acceptance testing.
- Load and security testing.

**Test Environment:** 
- OS: Windows/Linux
- Browser: Chrome, Firefox, Edge
- Server: Localhost/Vercel
- Database: MongoDB
- Backend: Node.js/Express.js

**Entry & Exit Criteria:** 
- Entry: Application deployed, core modules implemented.
- Exit: Critical bugs fixed, all test cases passed.

**Test Deliverables:** - Test Plan, Test Cases, Bug Report, Final Summary Report.

---

### Test Cases
![Test Cases](./assets/testcase.png)
---

## Gantt and PERT Charts

**Gantt Chart:** Provides a timeline visualization of tasks (unit testing, integration, UAT, documentation).

![Gantt Chart](./assets/gantt.png)

**PERT Chart:** Maps dependencies and critical paths in testing.

![PERT Chart](./assets/pert.png)

---

## Contributors

- [Prachit Bhujel](https://github.com/prachitvuzel)
- [Pratyoos Panta](https://github.com/pratyoos)
- [Sagar Mainali](https://github.com/)