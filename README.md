# USC Housing Digital Platform Initiative
**Role:** Technical Program Manager / Lead Analyst | **Project Budget:** $263,984

## 1. Executive Summary
Lead the strategic planning and lifecycle management of a mobile application designed to streamline the housing process for 50,000+ USC students. This initiative focused on centralizing housing reviews, roommate matching, and a student-to-student marketplace.

## 2. Technical Roadmap & Project Milestones
I managed the transition from initial discovery to a revised scope, handling a significant mid-project pivot.

| Phase | Key Deliverables | Status |
| :--- | :--- | :--- |
| **Discovery** | Stakeholder Surveys, User Requirements, Market Analysis | Completed |
| **Design** | Database Architecture, UI/UX Wireframes, Resource Planning | Completed |
| **Development** | Roommate Matching Logic, Marketplace Integration | Completed |
| **Deployment** | App Store Compliance, Post-Rollout Maintenance Plan | Completed |

## 3. Project Governance & Scope Management
A key highlight of this project was managing a **$76,836 budget increase** and a **2-month timeline extension**. I successfully reallocated resources from Marketing and R&D to cover engineering hours, ensuring project continuity.

### Risk Register & Mitigation
| Risk Category | Potential Impact | Mitigation Strategy |
| :--- | :--- | :--- |
| **Data Privacy** | Student identity exposure | Implemented strict student database verification protocols. |
| **Financial** | Budget overruns ($76k+) | Eliminated Legal Supervisor role; pivoted to internal USC Transportation SMEs. |
| **Technical** | Navigation inaccuracies | Integrated USC-specific parking and transportation data. |

## 4. Operational Flow
This diagram illustrates how I coordinated cross-functional teams to manage the platform's core services:

```mermaid
graph TD
    A[Student Profile] --> B{Verification API}
    B -->|Verified| C[Housing Reviews]
    B -->|Verified| D[Roommate Matcher]
    B -->|Verified| E[Student Marketplace]
    E --> F[Automated Fraud Detection]
    C & D & F --> G[Data Analytics Dashboard]
