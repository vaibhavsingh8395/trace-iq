# trace-iq
# 🎯 Trace-IQ | Autonomous Requirements Traceability & Impact Analyzer

> **Trace-IQ** is an enterprise-grade Business Analysis (BA) and requirements intelligence platform. It bridges the gap between high-level business stakeholder goals and technical engineering execution by automating Requirements Traceability Matrices (RTM), change-impact simulations, and scope verification.

---

## 🚀 Live Demo
Access the live production deployment hosted on GitHub Pages:  
🔗 **[Trace-IQ Enterprise Platform](https://vaibhavsingh8395.github.io/trace-iq/)**

---

## 📐 Scope of the Application

Traditional agile tools (like Jira or GitHub Issues) track tasks, but they lack visibility into *why* requirements exist, how they map to underlying architectural components, and what breaks when scope changes. Trace-IQ solves this by providing:

1. **End-to-End Traceability (RTM):** Automatically links business goals and user stories down to specific API endpoints and database schemas.
2. **Change Impact Simulator:** Instantly scans downstream architectural dependencies (such as database foreign keys, API gateways, and automated test suites) whenever a stakeholder modifies a requirement.
3. **Audit Lifecycle Tracking:** Maintains an immutable audit trail of scope modifications, stakeholder approvals, and requirement versions.
4. **Enterprise Export Suite:** One-click generation and download of RTM CSV reports and JSON specification packages for compliance and stakeholder sign-off.

---

## 🛠️ Technology Stack

* **Frontend:** Vanilla TypeScript / JavaScript, HTML5, CSS3 (Modern Dark-Mode Enterprise Design System with CSS Variables and Glassmorphism).
* **State & Storage:** LocalStorage-backed relational state management simulating a secure multi-tenant database partition.
* **Hosting & CI/CD:** GitHub Pages deployed via automated GitHub Actions workflows.

---

## 🕹️ How to Use the Application

### 1. Navigating the Dashboard
* **Traceability Matrix (RTM):** View, search, and manage all active system requirements mapped across user stories, risk levels, and components. Click **+ Ingest New Requirement** to add custom business rules.
* **Change Impact Simulator:** Select any requirement from the dropdown menu to simulate a scope modification. The engine instantly calculates affected technical components and engineering dependencies.
* **BA Metrics & Reports:** Review live KPIs (total requirements, coverage percentage, high-risk items) and export certified RTM CSV reports or JSON specification packages.
* **Requirements Audit Log:** Inspect the immutable chronological telemetry trail of all analyst edits and sign-offs.

### 2. Local Setup & Testing
To run or modify the application locally on your machine:

1. Clone the repository:
   ```bash
   git clone [https://github.com/vaibhavsingh8395/trace-iq.git](https://github.com/vaibhavsingh8395/trace-iq.git)
