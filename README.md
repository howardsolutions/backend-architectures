# Backend Architectures Notes

> Architectural BE DESIGN PRINCIPLES, CHALLENGES, REAL-WORLD APPLICATIONS while OFFERING detailed UNDERSTANDING
> of WHEN and HOW to implement them?

---

## 🎯 GOALS

Define the following:

- **WHAT** backend system architecture designs ARE
- **WHEN TO USE** the backend system architecture design
- **HOW to IMPLEMENT** backend system architecture design
- Explore **"COMMON"** backend system designs architecture
- Show **"evolution"** of a BACKEND'S system architecture

---

## 📌 WHAT ARE BACKEND ARCHITECTURE DESIGNS?

> The PROCESS of DEFINING the **Modularity**, **Interfaces**, **Data Flow** for a System to satisfy specified requirements.

### Importance

- Architecture designs provide a **structured approach** to solving complex problems, making it easier to understand and manage the overall system.

- Architecture designs can improve **efficiency and productivity** by REDUCING redundancy and facilitating code reuse.

- Architecture designs play a **KEY ROLE** in ENSURING that THE FINAL PRODUCT MEETS USER NEED and BUSINESS OBJECTIVES.

They help validate system complexity, ensure the design meets business objectives and user needs, save developer time and money by identifying potential issues before implementation, and provide a blueprint for building scalable and maintainable systems.

- Standardizing communication methods across systems, ensuring consistent error handling, choosing performant communication protocols, and minimizing the number of jumps data must take between components.

---

## 🏛️ MAIN 4 PRINCIPLES OF ARCHITECTURE DESIGNS

### 1. MODULARITY
Each component should have a specific task and be able to clearly explain what it does.

### 2. SCALABILITY
Designing a system to handle growth of traffic, ensuring individual modules can scale,
and preventing bottlenecks that impact system performance.

### 3. FLEXIBILITY
The system should be designed to accommodate future changes and features, avoiding scenarios where major refactoring is needed to implement new functionality.

### 4. ROBUSTNESS
Properly handling unexpected situations, creating clear error codes, ensuring systems can respond to errors without crashing, and creating a structured approach to error communication.

---

## ⚠️ KEY CHALLENGES

The key challenges include **complexity**, **adaptability**, **security**, **technology**, **resources**, and **stakeholders**.

### COMPLEXITY

Handling the intricate details and interdependencies in a SYSTEM can be COMPLEX.

The key challenges include complexity, adaptability, security, technology, resources, and stakeholders.

---

### ❓ What are the five tiers described in the system design approach?

**Frontend tier, backend tier, gateways, runners, and workers.**

---

### ❓ What is the key benefit of decoupling system components in architecture design?

It allows changing or growing different parts independently without affecting the entire system, providing more **flexibility** and **adaptability**.

---

### 🔐 Security

To satisfy legal requirements, meet SecOps policies, prevent unauthorized service access, protect sensitive data, and mitigate potential financial and legal risks.

### the primary goal of designing adaptable systems?

reduce developer friction, prevent system complexity, enable easier growth and modification, and allow focused changes 
to specific system components

## three key considerations when choosing a technology stack for a system

- Understanding the technology, experimentation, and the ability to support and troubleshoot it in production

## What is a critical but often overlooked aspect of resource management in technology development?
- Engineering hours and the total time spent on system development and maintenance

- To ensure buy-in, avoid challenging discussions, create a collaborative culture, and prevent stepping on anyone's toes

## What potential risk exists when selecting new or flashy technologies?

Unable to support the technology, lack of troubleshooting knowledge, and potential future complications

## What does resource management encompass beyond cloud resources?

Engineering resources, engineering time, manager planning, and overall financial investment in development

<hr />

# WHEN TO USE BACKEND ARCHITECTURE DESIGN?

- "greenfield" Starting a new project from scratch without existing constraints or impacts, where you can explore and build new systems without having to integrate with or modify existing infrastructure

## system designs help identify and address challenges in existing systems

- By helping to identify bottlenecks, analyze specific problems, introduce improvements like asynchronicity, decouple complex components, and potentially reduce engineering overhead by simplifying or delegating system complexities

## Potential benefits of improving system architecture regarding developer productivity

Reducing multi-point code updates, centralizing service logic, creating focused team responsibilities, minimizing repetitive lookup operations, and simplifying service interactions

## Why might an organization want to break complex problems into more manageable parts

To reduce engineering overhead, delegate complex tasks to specialized services or cloud providers, simplify system maintenance, and make the overall system architecture more modular and easier to understand

## How can system design documentation improve team communication?

By reducing reliance on tribal knowledge, providing clear architectural diagrams, facilitating easier team handoffs, documenting existing systems, and creating a shared understanding of system components and interactions

## KEY FACTORS TO CONSIDER WHEN DECIDING ON A BACK-END ARCHITECTURE DESIGN

project requirements (functionality, performance, security, scalability)
team expertise
budget, time constraints, project size and complexity
maintenance needs, technological choices, user feedback,
market trends, and legal/regulatory requirements.

### How do time constraints impact system design and development?

Time constraints help developers focus on essential tasks, 
prevent over-complication, enable faster iteration, and ensure efficient use of project resources. 
Developers should avoid spending too much time exploring and instead allocate time strategically to deliver the project effectively.

User feedback helps identify potential performance issues, user experience challenges, and architectural limitations. 
Understanding user experience can reveal problems like slow response times, which can impact user engagement and satisfaction, especially given modern users' short attention spans.

When evaluating technological trends, developers should be aware of new technologies without blindly adopting them. It's crucial to understand not just the potential benefits but also the maintenance challenges, implementation complexity, and whether the technology truly solves the specific project needs.

<hr />

# HOW TO IMPLEMENT BACKEND ARCHITECTURE DESIGN?

## Design Stages

### 1. Research

#### Setting Requirements: 

Identify the PRIMARY PURPOSE and SCOPE of the system.

- Understand the needs and expectations of the end-users of the system.

- Determine the functionality that the system needs to provide to meet the end-users needs.

- Specify the performance levels that the system needs to achieve.

- Identify any constraints or limitations , such as budget, resources, or time.

- Consider the scalability needs of the system - how it can grow and adapt to increased demand.

- Determine any security requirements to protect data and process within the system.

- Identify any regulatory or compliance requirements that the system needs to meet.

- Specify the requirements for integrating the new system with existing systems.

#### EXPLORATION: 

- Research and testing of new technologies. After setting requirements.

- experimenting with new methodologies and tools.

- Determine if the goal is to improve the system design ENTIRELY (INNOVATION) or MAKE SMALL CHANGES where needed (iteration).

#### TECHNICAL DOCMENTATIONS

- Used for understanding possible explored solutions or ideas which keep the project on path.

- Provide detailed descriptions of the explored systems, including architectures, modules, interfaces, and data relevant to the project.

- to reference for the development team and other stakeholders.

- facillitate communication and collaboration.

Exploration and research of new technologies, methodologies, and potential system improvements, followed by writing technical documentation to capture findings and potential solutions

#### How long should the research and requirements defining phase typically take?
Between one week to one month, with the goal of avoiding excessive time spent without producing actionable insights

#### What is the recommended approach to defining system architecture?

Create a 'jigsaw' approach where individual components are mapped out, using workflows, charts, and diagrams to understand how different elements 
interface and work together, ensuring high modularity and compatibility

###  the primary steps to take after setting project requirements?

- Exploration and research of new technologies, methodologies, and potential system improvements, followed by writing technical documentation to capture findings and potential solutions

### key considerations should be made during the exploration phase of system design?

- Determine whether the goal is to improve the entire system design, innovate, or make small incremental changes, while being mindful of project scope, time constraints, and overall company needs

###  the primary purpose of creating technical documents during system exploration?
To document explored systems, architectures, models, interfaces, and data; facilitate communication and collaboration; and provide a reference for future discussions and decision-making

### How long should the research and requirements defining phase typically take?
Between one week to one month, with the goal of avoiding excessive time spent without producing actionable insights

### What is the recommended approach to defining system architecture?

Create a 'jigsaw' approach where individual components are mapped out, using workflows, charts, and diagrams to understand how different elements interface and work together, ensuring high modularity and compatibility


### 2. Implement


### 3. Iterate