# Backend Architectures Notes

> Architectural BE DESIGN PRINCIPLES, CHALLENGES, REAL-WORLD APPLICATIONS while OFFERING detailed UNDERSTANDING
> of **WHEN** and **HOW** to implement them?

---

<details open>
<summary>🎯 GOALS</summary>

Define the following:

- **WHAT** backend system architecture designs ARE
- **WHEN TO USE** the backend system architecture design
- **HOW to IMPLEMENT** backend system architecture design
- Explore **"COMMON"** backend system designs architecture
- Show **"evolution"** of a BACKEND'S system architecture

</details>

---

<details open>
<summary>📌 WHAT ARE BACKEND ARCHITECTURE DESIGNS?</summary>

> The PROCESS of DEFINING the **Modularity**, **Interfaces**, **Data Flow** for a System to satisfy specified requirements.

### 💡 Importance

- Architecture designs provide a **structured approach** to solving complex problems, making it easier to understand and manage the overall system.
- Architecture designs can improve **efficiency and productivity** by REDUCING redundancy and facilitating code reuse.
- Architecture designs play a **KEY ROLE** in ENSURING that THE FINAL PRODUCT MEETS USER NEED and BUSINESS OBJECTIVES.

They help validate system complexity, ensure the design meets business objectives and user needs, save developer time and money by identifying potential issues before implementation, and provide a blueprint for building scalable and maintainable systems.

- Standardizing communication methods across systems, ensuring consistent error handling, choosing performant communication protocols, and minimizing the number of jumps data must take between components.

</details>

---

<details open>
<summary>🏛️ MAIN 4 PRINCIPLES OF ARCHITECTURE DESIGNS</summary>

<details open>
<summary>1. 🧩 MODULARITY</summary>

Each component should have a specific task and be able to clearly explain what it does.

</details>

<details open>
<summary>2. 📈 SCALABILITY</summary>

Designing a system to handle growth of traffic, ensuring individual modules can scale,
and preventing bottlenecks that impact system performance.

</details>

<details open>
<summary>3. 🔄 FLEXIBILITY</summary>

The system should be designed to accommodate future changes and features, avoiding scenarios where major refactoring is needed to implement new functionality.

</details>

<details open>
<summary>4. 🛡️ ROBUSTNESS</summary>

Properly handling unexpected situations, creating clear error codes, ensuring systems can respond to errors without crashing, and creating a structured approach to error communication.

</details>

</details>

---

<details open>
<summary>⚠️ KEY CHALLENGES</summary>

The key challenges include **complexity**, **adaptability**, **security**, **technology**, **resources**, and **stakeholders**.

<details open>
<summary>🔀 COMPLEXITY</summary>

Handling the intricate details and interdependencies in a SYSTEM can be COMPLEX.

The key challenges include complexity, adaptability, security, technology, resources, and stakeholders.

</details>

<details open>
<summary>❓ What are the five tiers described in the system design approach?</summary>

**Frontend tier, backend tier, gateways, runners, and workers.**

</details>

<details open>
<summary>❓ What is the key benefit of decoupling system components in architecture design?</summary>

It allows changing or growing different parts independently without affecting the entire system, providing more **flexibility** and **adaptability**.

</details>

<details open>
<summary>🔐 Security</summary>

To satisfy legal requirements, meet SecOps policies, prevent unauthorized service access, protect sensitive data, and mitigate potential financial and legal risks.

</details>

<details open>
<summary>❓ What is the primary goal of designing adaptable systems?</summary>

Reduce developer friction, prevent system complexity, enable easier growth and modification, and allow focused changes
to specific system components.

</details>

<details open>
<summary>💻 Three key considerations when choosing a technology stack for a system</summary>

- Understanding the technology, experimentation, and the ability to support and troubleshoot it in production

</details>

<details open>
<summary>⏱️ What is a critical but often overlooked aspect of resource management in technology development?</summary>

- Engineering hours and the total time spent on system development and maintenance
- To ensure buy-in, avoid challenging discussions, create a collaborative culture, and prevent stepping on anyone's toes

</details>

<details open>
<summary>⚡ What potential risk exists when selecting new or flashy technologies?</summary>

Unable to support the technology, lack of troubleshooting knowledge, and potential future complications

</details>

<details open>
<summary>💰 What does resource management encompass beyond cloud resources?</summary>

Engineering resources, engineering time, manager planning, and overall financial investment in development

</details>

</details>

<hr />

<details open>
<summary>🗓️ WHEN TO USE BACKEND ARCHITECTURE DESIGN?</summary>

- **"greenfield"** Starting a new project from scratch without existing constraints or impacts, where you can explore and build new systems without having to integrate with or modify existing infrastructure

<details open>
<summary>🔍 How system designs help identify and address challenges in existing systems</summary>

By helping to identify bottlenecks, analyze specific problems, introduce improvements like asynchronicity, decouple complex components, and potentially reduce engineering overhead by simplifying or delegating system complexities

</details>

<details open>
<summary>📈 Potential benefits of improving system architecture regarding developer productivity</summary>

Reducing multi-point code updates, centralizing service logic, creating focused team responsibilities, minimizing repetitive lookup operations, and simplifying service interactions

</details>

<details open>
<summary>🧩 Why might an organization want to break complex problems into more manageable parts</summary>

To reduce engineering overhead, delegate complex tasks to specialized services or cloud providers, simplify system maintenance, and make the overall system architecture more modular and easier to understand

</details>

<details open>
<summary>💬 How can system design documentation improve team communication?</summary>

By reducing reliance on tribal knowledge, providing clear architectural diagrams, facilitating easier team handoffs, documenting existing systems, and creating a shared understanding of system components and interactions

</details>

<details open>
<summary>🔑 KEY FACTORS TO CONSIDER WHEN DECIDING ON A BACK-END ARCHITECTURE DESIGN</summary>

- **Project requirements:** functionality, performance, security, scalability
- **Team expertise**
- **Budget, time constraints, project size and complexity**
- **Maintenance needs, technological choices, user feedback**
- **Market trends, and legal/regulatory requirements**

<details open>
<summary>⏰ How do time constraints impact system design and development?</summary>

Time constraints help developers focus on essential tasks,
prevent over-complication, enable faster iteration, and ensure efficient use of project resources.
Developers should avoid spending too much time exploring and instead allocate time strategically to deliver the project effectively.

User feedback helps identify potential performance issues, user experience challenges, and architectural limitations.
Understanding user experience can reveal problems like slow response times, which can impact user engagement and satisfaction, especially given modern users' short attention spans.

When evaluating technological trends, developers should be aware of new technologies without blindly adopting them. It's crucial to understand not just the potential benefits but also the maintenance challenges, implementation complexity, and whether the technology truly solves the specific project needs.

</details>

</details>

</details>

<hr />

<details open>
<summary>🛠️ HOW TO IMPLEMENT BACKEND ARCHITECTURE DESIGN?</summary>

## Design Stages

<details open>
<summary>1. 🔬 Research</summary>

<details open>
<summary>📋 Setting Requirements</summary>

Identify the **PRIMARY PURPOSE** and **SCOPE** of the system.

- Understand the needs and expectations of the end-users of the system.
- Determine the functionality that the system needs to provide to meet the end-users needs.
- Specify the performance levels that the system needs to achieve.
- Identify any constraints or limitations , such as budget, resources, or time.
- Consider the scalability needs of the system - how it can grow and adapt to increased demand.
- Determine any security requirements to protect data and process within the system.
- Identify any regulatory or compliance requirements that the system needs to meet.
- Specify the requirements for integrating the new system with existing systems.

</details>

<details open>
<summary>⚙️ IMPLEMENTING SYSTEM DESIGNS</summary>

- Choose appropriate design.
- Define the architecture
- Develop the architecture
- Test the architecture
- Deploy the architecture
- Maintain the architecture.

</details>

<details open>
<summary>🧪 EXPLORATION</summary>

- Research and testing of new technologies. After setting requirements.
- Experimenting with new methodologies and tools.
- Determine if the goal is to improve the system design ENTIRELY (**INNOVATION**) or MAKE SMALL CHANGES where needed (**iteration**).

</details>

<details open>
<summary>📄 TECHNICAL DOCUMENTATION</summary>

- Used for understanding possible explored solutions or ideas which keep the project on path.
- Provide detailed descriptions of the explored systems, including architectures, modules, interfaces, and data relevant to the project.
- To reference for the development team and other stakeholders.
- Facilitate communication and collaboration.

Exploration and research of new technologies, methodologies, and potential system improvements, followed by writing technical documentation to capture findings and potential solutions

</details>

<details open>
<summary>❓ How long should the research and requirements defining phase typically take?</summary>

Between one week to one month, with the goal of avoiding excessive time spent without producing actionable insights

</details>

<details open>
<summary>❓ What is the recommended approach to defining system architecture?</summary>

Create a **'jigsaw' approach** where individual components are mapped out, using workflows, charts, and diagrams to understand how different elements
interface and work together, ensuring high modularity and compatibility

</details>

<details open>
<summary>❓ What are the primary steps to take after setting project requirements?</summary>

Exploration and research of new technologies, methodologies, and potential system improvements, followed by writing technical documentation to capture findings and potential solutions

</details>

<details open>
<summary>❓ What key considerations should be made during the exploration phase of system design?</summary>

Determine whether the goal is to improve the entire system design, innovate, or make small incremental changes, while being mindful of project scope, time constraints, and overall company needs

</details>

<details open>
<summary>❓ What is the primary purpose of creating technical documents during system exploration?</summary>

To document explored systems, architectures, models, interfaces, and data; facilitate communication and collaboration; and provide a reference for future discussions and decision-making

</details>

<details open>
<summary>❓ How long should the research and requirements defining phase typically take?</summary>

Between one week to one month, with the goal of avoiding excessive time spent without producing actionable insights

</details>

<details open>
<summary>❓ What is the recommended approach to defining system architecture?</summary>

Create a **'jigsaw' approach** where individual components are mapped out, using workflows, charts, and diagrams to understand how different elements interface and work together, ensuring high modularity and compatibility

</details>

</details>

<details open>
<summary>2. 🏗️ Implement</summary>

</details>

<details open>
<summary>3. 🔁 Iterate</summary>

</details>

</details>
