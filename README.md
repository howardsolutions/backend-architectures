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

