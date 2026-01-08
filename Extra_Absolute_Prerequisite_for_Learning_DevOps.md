# Absolute Prerequisites for Learning DevOps

## 1. Roles in an Organization

As a DevOps engineer, you don't interact directly with customers. Requirements flow through several roles before reaching the technical teams.

### Core Roles and Responsibilities:

* **Customer:** The source of feedback and requirements (e.g., a request for "15-minute grocery delivery").
* **Business Analyst (BA):** Interacts with customers and marketing to gather requirements. They create the **BRD (Business Requirement Document)**.
* **Product Manager (PM):** Defines the product vision and prioritizes the BRD items based on market trends and competitors.
* **Product Owner (PO):** Converts the PM's vision into actionable items called **Epics** or **Features**. They manage the product backlog.
* **Solutions/Software Architect:** Deep-dives into the technical side, defining the **HLD (High-Level Design)** and **LLD (Low-Level Design)** structure.
* **Scrum Team:** A cross-functional team that works together to complete the requirement. It typically includes:
* **Developers:** Build the feature.
* **DevOps Engineers:** Provide infrastructure (Kubernetes clusters, Docker files, Git repos).
* **QA/QE Engineers:** Test the features.
* **Database Administrator (DBA):** Manages data systems.
* **Technical Writers:** Document the new features for end-users.


* **SRE (Site Reliability Engineer):** Ensures post-deployment availability, reliability, and monitoring through dashboards and metrics.

---

## 2. Software Development Life Cycle (SDLC) Deep Dive

The SDLC is a structured process to ensure software is built correctly and efficiently.

### The 6 Phases:

1. **Planning:** Gathering initial requirements.
2. **Analysis:** Determining if the requirement is feasible and valuable.
3. **Design:** Architects create HLD/LLD technical frameworks.
4. **Implementation:** The actual coding and infrastructure setup by Developers and DevOps.
5. **Testing & Integration:** Validating the code and merging it.
6. **Maintenance:** Ongoing support and reliability checks by SREs.

**DevOps Impact:** DevOps engineers identify gaps in the SDLC to speed up delivery (e.g., reducing a 3-month cycle to 2 months) by automating manual handoffs between Dev and QA using **CI/CD pipelines**.

---

## 3. Project Management with Jira

Jira is the most popular tool used to track work, provide visibility to management, and ensure accountability.

### Key Jira Concepts:

* **Organization & Project:** The high-level structure (e.g., Organization: *Amazon*, Project: *Amazon Fresh*).
* **Epic:** A large requirement that can be broken down into smaller tasks (e.g., "Implement 15-minute delivery").
* **Story/Task:** Small, actionable work items. For a DevOps engineer, this might be "Create EKS Cluster using Terraform."
* **Backlog:** A list of all pending stories and epics created by the PO.
* **Sprints:** A set period (usually 2–3 weeks) where the team commits to finishing specific items from the backlog.
* **Sprint Planning:** A meeting at the start of a sprint to decide which tasks to pull from the backlog.
* **Sprint Retrospective:** A meeting at the end of a sprint to review what was completed and what can be improved.

### How DevOps Gets Work:

DevOps engineers receive tasks during **Sprint Planning**. When a developer realizes they need a specific database or infrastructure to build a feature, they request a story be created and assigned to the DevOps engineer.

---

## 4. Summary for Career Readiness

Understanding how requirements move from a customer to a Jira ticket makes you a more confident engineer. In interviews, being able to explain the relationship between a **Product Owner**, **Developer**, and **DevOps Engineer** within a **Scrum Team** demonstrates professional maturity beyond just knowing technical tools.