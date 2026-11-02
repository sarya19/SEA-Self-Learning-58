# SEA – Self Learning Activity 58

**Subject:** Software Engineering and Architecture (SEA)  
**Activity:** Self Learning Activity  
**Roll Number:** 58

---

## Table of Contents

1. [Comparison of Agile vs DevOps](#1-comparison-of-agile-vs-devops)
2. [Case Study of JIRA and Asana](#2-case-study-of-jira-and-asana)
3. [User Stories and Acceptance Criteria](#3-user-stories-and-acceptance-criteria)
4. [Advanced Requirement Elicitation Techniques](#4-advanced-requirement-elicitation-techniques)
5. [Requirement Traceability Matrix (RTM)](#5-requirement-traceability-matrix-rtm)
6. [Tools for Requirement Management](#6-tools-for-requirement-management)

---

## 1. Comparison of Agile vs DevOps

### 1.1 Agile

Agile is a software development approach that uses short, iterative cycles to develop software. It emphasizes adaptability, customer feedback, teamwork, and continuous improvement.

**Typical Agile Cycle:**

Requirements → Planning → Development → Testing → Review → Feedback → Next Iteration

Agile focuses mainly on software planning and development through smaller iterations or sprints.

### 1.2 DevOps

DevOps combines Development and Operations to improve software delivery speed, reliability, and efficiency.

**Typical DevOps Flow:**

Plan → Code → Build → Test → Release → Deploy → Operate → Monitor → Feedback

DevOps emphasizes automation, Continuous Integration (CI), Continuous Delivery (CD), collaboration, and continuous monitoring.

### 1.3 Agile vs DevOps

| Basis | Agile | DevOps |
|---|---|---|
| Meaning | Software development methodology | Culture, practices, and supporting tools |
| Main Focus | Building software | Development, delivery, and operations |
| Goal | Adapt to changing requirements | Faster and reliable delivery |
| Teams | Developers, testers, product owners | Development, operations, testing, security |
| Development | Iterative and incremental | Continuous and automated |
| Deployment | Not the central concern | Primary focus |
| Automation | Applied where needed | Emphasized throughout the lifecycle |
| Feedback | Customers and stakeholders | Customers, systems, and operations |
| Work Cycle | Sprints or iterations | Continuous lifecycle |

**Relationship:** Agile and DevOps complement each other. Agile guides what to build and how to develop it incrementally, while DevOps supports building, testing, deploying, operating, and monitoring the software.

**Example:**
- Agile: A customer requests a new online payment feature.
- DevOps: The team builds, tests, deploys, monitors, and improves the feature.

---

## 2. Case Study of JIRA and Asana

### 2.1 JIRA

JIRA, developed by Atlassian, is a project management and issue-tracking tool widely used by software development teams to manage tasks, user stories, issues, and Agile workflows.

**Case Study: Online Shopping Application**

Consider a company developing an online shopping application with the following features:

- User Registration
- User Login
- Product Search
- Shopping Cart
- Online Payment
- Order Tracking

**Example User Story:**

As a customer, I want to add products to my shopping cart so that I can purchase them later.

**Tasks:**
1. Design the shopping cart interface.
2. Develop the Add-to-Cart functionality.
3. Set up database operations.
4. Calculate the total price.
5. Test the shopping cart.

**Task Workflow:**

`To Do → In Progress → Testing → Done`

JIRA provides centralized project tracking and supports backlogs, user stories, sprints, Scrum, and Kanban workflows.

### 2.2 Asana

Asana is a project and work management tool that helps teams organize tasks, responsibilities, and deadlines.

**Case Study: Mobile Application Launch**

Consider a company preparing to launch a mobile application. The project includes market research, UI/UX design, development, testing, marketing, and product launch.

| Task | Responsible Team | Status |
|---|---|---|
| Market Research | Marketing Team | Completed |
| UI/UX Design | Design Team | In Progress |
| Application Development | Development Team | In Progress |
| Testing | QA Team | Not Started |
| Marketing Campaign | Marketing Team | Not Started |

Asana helps team members understand task ownership, progress, and pending work.

### 2.3 JIRA vs Asana

| Feature | JIRA | Asana |
|---|---|---|
| Main Purpose | Software and project tracking | General project management |
| Best Suited For | Software development teams | Cross-functional teams |
| User Stories | Strongly supported | Handled as tasks |
| Scrum/Kanban | Strong support | Project-style workflows |
| Issue Tracking | Strong | Primarily task-based |
| Sprint Management | Strong | Less central |
| Main Strength | Agile software development | Task and project coordination |

---

## 3. User Stories and Acceptance Criteria

### 3.1 User Stories

A user story describes a requirement from the perspective of the person using the system. It explains what the user wants and why it is valuable.

**Common Format:**

`As a [type of user], I want [goal], so that [benefit].`

**Example:**

As a customer, I want to add products to my shopping cart so that I can purchase multiple products together.

- User: Customer
- Requirement: Add products to the cart
- Benefit: Purchase multiple products together

**Characteristics of an Effective User Story:**

1. Clear – Easy to understand.
2. Concise – Contains necessary information.
3. User-focused – Addresses actual user needs.
4. Valuable – Provides meaningful benefits.
5. Testable – Can be verified through testing.
6. Independent – Avoids unnecessary dependencies.
7. Prioritized – Important requirements are addressed first.

### 3.2 Acceptance Criteria

Acceptance criteria define specific conditions that a user story must satisfy before it can be considered complete and accepted.

**Example User Story:**

As a customer, I want to add products to my shopping cart so that I can purchase them later.

**Acceptance Criteria:**

1. The customer can add an available product to the cart.
2. The selected product appears in the cart.
3. The customer can increase or decrease the quantity.
4. The cart displays the correct total price.
5. The customer can remove a product.
6. An unavailable product cannot be added to the cart.

Acceptance criteria make requirements specific, measurable, and testable.

---

## 4. Advanced Requirement Elicitation Techniques

Requirement elicitation is the process of gathering, understanding, and documenting stakeholders' needs and expectations.

Two important techniques are Interviews and Ethnography.

### 4.1 Interviews

An interview is a technique in which a requirements analyst directly questions stakeholders to understand their needs, expectations, problems, and priorities.

**Types of Interviews:**

1. Structured Interview – Uses a fixed list of prepared questions.
2. Unstructured Interview – Allows an open-ended conversation.
3. Semi-structured Interview – Uses prepared questions while allowing additional questions.

**Interview Process:**

1. Identify stakeholders.
2. Prepare relevant questions.
3. Conduct the interview.
4. Record important information.
5. Analyze collected information.
6. Validate requirements with stakeholders.
7. Document final requirements.

**Example:**

For an online banking system, an analyst may interview customers and bank staff to identify requirements related to login, fund transfers, transaction history, notifications, security, and account management.

**Advantages:**
- Provides detailed information.
- Allows immediate clarification.
- Helps uncover hidden requirements.
- Provides direct stakeholder feedback.

**Limitations:**
- Can be time-consuming.
- Stakeholders may provide biased or incomplete answers.
- Results depend on question quality.

### 4.2 Ethnography

Ethnography involves observing users directly in their actual working environment to understand how they perform tasks.

Unlike interviews, which depend on what users describe, ethnography focuses on what users actually do.

**Example: Hospital Management System**

When developing software for hospital nurses, an analyst observes their daily activities and discovers that nurses:

- Need patient information readily available.
- Frequently move between departments.
- Have limited time for data entry.
- Need immediate alerts for important events.

These observations reveal practical requirements that may not emerge during interviews.

**Advantages:**
- Captures actual user behaviour.
- Reveals hidden requirements.
- Provides an understanding of daily workflows.
- Works well in complex environments.

**Limitations:**
- Can be time-consuming.
- Users may behave differently when observed.
- Requires access to the actual work environment.
- Observational data can be difficult to analyze.

---

## 5. Requirement Traceability Matrix (RTM)

### 5.1 Definition

A Requirement Traceability Matrix (RTM) is a table or document that maps requirements to related project artifacts, including design components, development activities, and test cases.

Its primary purpose is to ensure that every requirement is implemented and tested.

**Requirement Traceability Flow:**

`Requirement → Design → Development → Test Case → Test Result`

### 5.2 Example of RTM

Consider an online shopping system.

| Requirement ID | Requirement | Module | Test Case ID | Status |
|---|---|---|---|---|
| REQ-01 | User Registration | Registration | TC-01 | Completed |
| REQ-02 | User Login | Login | TC-02 | Completed |
| REQ-03 | Product Search | Search | TC-03 | Completed |
| REQ-04 | Add Product to Cart | Cart | TC-04 | In Progress |
| REQ-05 | Online Payment | Payment | TC-05 | Pending |

### 5.3 Importance of RTM

RTM helps to:

- Ensure every requirement is accounted for.
- Link requirements to test cases.
- Identify missing requirements and testing gaps.
- Track requirements throughout the project.
- Manage requirement changes.
- Improve overall software quality.
- Verify that the final product meets specified requirements.

---

## 6. Tools for Requirement Management

Requirement management tools help organizations capture, organize, prioritize, track, trace, and manage changes to requirements throughout the Software Development Life Cycle (SDLC).

**Examples:**
- IBM DOORS
- JIRA
- Azure DevOps
- Jama Connect
- Polarion

### 6.1 IBM DOORS

IBM Engineering Requirements Management DOORS is a tool designed to capture, organize, analyze, trace, and manage project requirements.

It helps teams maintain relationships between requirements and other project artifacts.

**Major Features of IBM DOORS:**

1. Requirement Management – Creates, organizes, stores, and manages project requirements.
2. Requirement Traceability – Links requirements to related requirements and project artifacts.
3. Change Management – Tracks requirement changes and helps identify their impact.
4. Requirement Analysis – Supports reviewing requirements and their relationships.
5. Collaboration – Enables stakeholders to work with requirements throughout the project.

**Example: Automotive Software Project**

An automotive software project may contain requirements related to:

- Vehicle Safety
- Braking Systems
- Sensors
- Performance
- Security

IBM DOORS helps organize these requirements and maintain traceability between requirements, development work, and testing.

When a requirement changes, the team can trace related information to understand which other project components may be affected.

**Advantages of IBM DOORS:**

- Centralized requirement management.
- Requirement traceability.
- Change tracking.
- Better-organized requirements.
- Improved collaboration.
- Support for large and complex projects.

---

## Conclusion

This self-learning activity explores Agile and DevOps, project management tools such as JIRA and Asana, effective user stories and acceptance criteria, advanced requirement elicitation techniques, Requirement Traceability Matrices, and requirement management tools such as IBM DOORS. These concepts help improve requirement clarity, project coordination, traceability, and software quality throughout the Software Development Life Cycle.

---

**Subject:** Software Engineering and Architecture  
**Activity:** Self Learning Activity 58
