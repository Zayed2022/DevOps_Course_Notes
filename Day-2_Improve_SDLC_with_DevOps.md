# Day 2 | Improving SDLC with DevOps

## 1. What is SDLC?
**Software Development Life Cycle (SDLC)** is a standard process or framework followed by the software industry to **design, develop, and test** high-quality software. 

* **Goal:** To deliver a product that meets or exceeds customer expectations within the shortest possible time and cost.
* **Standardization:** Whether at a startup or a major firm like Amazon or Tesla, these phases provide the roadmap for software creation.

---

## 2. The Phases of SDLC

### A. Planning & Requirement Gathering
* **Who:** Product Owners, Business Analysts (BAs), and Senior Members.
* **Activity:** Gathering feedback from customers and stakeholders. 
* **Example:** Deciding if an e-commerce site should add a "Kids Section" based on market research.

### B. Defining
* **Activity:** Translating requirements into a formal document called the **SRS (Software Requirement Specification)**.

### C. Designing
* **High-Level Design (HLD):** System architecture, database selection, and scalability plans (e.g., "How will we handle Christmas traffic?").
* **Low-Level Design (LLD):** Specific functional details, module logic, and API arguments.

### D. Building (Development)
* **Who:** Software Developers.
* **Activity:** Writing the actual code.
* **Tooling:** Developers push their code to a **Source Code Repository** (typically **Git**) so the team can collaborate.

### E. Testing
* **Who:** QE (Quality Assurance) Engineers.
* **Activity:** The application is deployed to a staging/virtual server to check for bugs and ensure high quality before the customer sees it.

### F. Deployment
* **Activity:** The application is moved to the **Production Server** where it becomes live for the end customers.

---

## 3. Where Does DevOps Fit In?

While a DevOps engineer should understand the entire cycle, their **primary focus** is on the automation of the final three stages:

| Phase | DevOps Responsibility |
| :--- | :--- |
| **Building** | Automating the process of taking code from Git and preparing it for deployment. |
| **Testing** | Ensuring automated test scripts run every time code is changed (Continuous Testing). |
| **Deployment** | Removing manual steps to move code into production (Continuous Delivery). |

### Key Takeaway for DevOps Engineers:
Your goal is **Automation = Efficiency**. By automating these phases, you reduce the "manual intervention" that typically slows down software releases.

---

## 4. Modern SDLC: Agile Methodology
Most organizations today follow **Agile**. 
* Instead of waiting months for a "Waterfall" release, Agile breaks the SDLC into small chunks (Sprints).
* DevOps is essential for Agile because it allows the team to go through the **Plan → Design → Build → Test → Deploy** cycle rapidly and frequently.

---

## 5. Interview Summary
When asked about SDLC in a DevOps interview, you should say:
> "SDLC is the standard industry process to design, develop, and test software. As a DevOps engineer, I focus on the **Building, Testing, and Deployment** phases. My job is to automate these pillars to ensure the organization can deliver high-quality code with maximum efficiency and minimal manual error."