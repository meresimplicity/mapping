# Business Requirements & Process Improvement

## Retail Inventory Replenishment Process Improvement

### Business Systems Analyst Case Study

## Business Problem

Store associates rely on manual inventory checks and multiple communication methods to identify and coordinate replenishment needs.

This can result in:

* Delayed identification of replenishment needs
* Inconsistent prioritization
* Missed or duplicate work
* Limited visibility into outstanding tasks
* Manual communication overhead
* Difficulty measuring replenishment performance

The objective of this case study is to redesign the process and define system requirements for a more consistent, visible, and measurable replenishment workflow.

> **Data and scenario note:** This is a fictional case study created for portfolio purposes. It does not contain proprietary employer information.

---

# BSA Approach

The analysis follows a standard Business Systems Analysis lifecycle:

**Business Problem**
↓
**Stakeholders & Scope**
↓
**Current-State Analysis**
↓
**Pain Points**
↓
**Business Requirements**
↓
**Functional Requirements**
↓
**User Stories**
↓
**Acceptance Criteria**
↓
**Future-State Process**
↓
**Success Metrics**

---

# Stakeholders

Key stakeholders identified for the solution include:

* Store Associates
* Department Supervisors
* Store Management
* Inventory/Operations Teams
* Merchandising
* IT/Application Support

Each stakeholder has different responsibilities and information needs within the replenishment process.

---

# Current-State Analysis

The current process relies heavily on manual observation, system lookups, informal communication, and supervisor follow-up.

### Major Pain Points

| Area           | Current Challenge                                           |
| -------------- | ----------------------------------------------------------- |
| Identification | Replenishment needs may be identified inconsistently        |
| Communication  | Multiple communication methods can cause missed information |
| Prioritization | Priorities may vary between users or shifts                 |
| Assignment     | Task ownership may not be clearly documented                |
| Tracking       | Limited visibility into outstanding work                    |
| Completion     | Completion may be communicated informally                   |
| Reporting      | Limited historical performance information                  |
| Labor          | Time is spent identifying and coordinating work             |

The analysis identified the need for a standardized workflow rather than simply another inventory report.

---

# Requirements Analysis

## Business Requirements

The solution should:

* Improve replenishment visibility
* Standardize task prioritization
* Establish task accountability
* Improve task tracking
* Reduce manual communication
* Improve management reporting
* Support product availability

## Functional Requirements

The proposed solution should support:

* Inventory data display
* Replenishment alerts
* Task creation
* Task prioritization
* Task assignment
* Task status management
* Completion recording
* Escalation
* Task search and filtering
* Management dashboards
* Role-based access
* Audit history

---

# User Stories

Example:

> **As a department supervisor, I want to view prioritized replenishment tasks so that I can allocate my team's time effectively.**

User stories were developed for associates, supervisors, managers, and operations stakeholders.

Acceptance criteria use **Given / When / Then** scenarios to make requirements testable.

Example:

> **Given** an open replenishment task exists,
> **When** an authorized supervisor assigns the task to an associate,
> **Then** the system records the associate as the task owner.

---

# Data & Requirements Accuracy

A key consideration in this project is **inventory data accuracy**.

A replenishment system can produce incorrect business outcomes if the underlying inventory information is inaccurate or stale.

The proposed requirements therefore address:

* Inventory source
* Data timestamp
* Missing data
* Stale inventory information
* Inventory discrepancies
* Duplicate tasks
* Exception handling
* Audit history

This demonstrates an important BSA principle:

> **A system can execute requirements correctly and still produce poor business outcomes if the underlying data or business rules are incorrect.**

---

# Future-State Process

The proposed process converts inventory signals into structured, trackable work:

**Inventory Data**
→ **Evaluate Replenishment Criteria**
→ **Create Task**
→ **Prioritize**
→ **Assign**
→ **Execute**
→ **Complete / Exception**
→ **Escalate if Necessary**
→ **Management Reporting**

The future state introduces:

* Standardization
* Centralized visibility
* Clear ownership
* Exception handling
* Performance measurement
* Auditability

---

# Success Metrics

Recommended measures include:

| KPI                         | Purpose                 |
| --------------------------- | ----------------------- |
| Average completion time     | Process efficiency      |
| On-time completion rate     | Execution reliability   |
| Overdue task percentage     | Workflow effectiveness  |
| Unable-to-complete rate     | Exception analysis      |
| Product availability        | Customer-facing outcome |
| Tasks per labor hour        | Operational efficiency  |
| Manual communication events | Administrative burden   |

---

# Project Artifacts

### Requirements

* [`business_requirements.md`](requirements/business_requirements.md)
* [`user_stories.md`](requirements/user_stories.md)

### Process Analysis

* [`current_state.md`](process/current_state.md)
* [`future_state.md`](process/future_state.md)

---

# Skills Demonstrated

### Business Analysis

* Requirements elicitation
* Requirements documentation
* Stakeholder analysis
* Scope definition
* Current-state analysis
* Future-state process design
* Process improvement
* Requirements traceability
* Business rules
* Exception analysis

### Agile / SDLC

* User stories
* Acceptance criteria
* Definition of Done
* Functional requirements
* Non-functional requirements
* Requirement validation

### Business Systems Analysis

* Translating business needs into system requirements
* Identifying data dependencies
* Designing workflow improvements
* Defining user roles and permissions
* Developing measurable success criteria
* Connecting requirements to business outcomes

---

# Analyst Takeaway

The purpose of this case study was not simply to document requirements.

The objective was to demonstrate the complete thought process of a Business Systems Analyst:

**Understand the business problem → analyze the current process → identify pain points → define requirements → translate requirements into testable functionality → design the future state → establish measurable outcomes.**

The project also demonstrates the importance of validating **data accuracy, business rules, exceptions, and stakeholder needs** before a solution moves into development.
