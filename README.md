# IT Help Desk Ticketing System Lab

## Overview

This project demonstrates a simulated IT Help Desk ticket workflow using **Spiceworks Cloud Help Desk**.

The lab focuses on practical Level 1 Help Desk activities including ticket creation, categorization, prioritization, resolution documentation, ticket closure, and escalation.

## Objectives

* Create and categorize support tickets
* Assign appropriate ticket priority
* Document troubleshooting and resolutions
* Confirm resolution with the user
* Properly close resolved tickets
* Recognize when an issue requires escalation
* Provide relevant information when escalating a ticket

## Tools Used

* **Spiceworks Cloud Help Desk**
* Web Browser

---

## Activity 1 — Simulate a Ticket Creation

### Objective

Understand how support tickets are created, categorized, and prioritized.

### Scenario

A user reported that their monitor was not functioning.

### Ticket Details

* **Subject:** Monitor isn't working (Comp_01)
* **Category:** Hardware
* **Priority:** High
* **Issue:** User reported that the monitor was not displaying anything after basic troubleshooting.
* **Attachment:** Supporting screenshot

### Evidence

<img width="1917" height="1038" alt="SS01 - Simulated Ticket Creation" src="https://github.com/user-attachments/assets/05284332-c501-46b7-b66f-8830f4f3efad" />



---

## Activity 2 — Ticket Closure Checklist

### Objective

Ensure a resolved ticket is properly documented and closed.

### Tasks Performed

* Confirmed the issue was resolved
* Documented troubleshooting and resolution notes
* Updated the ticket with the resolution
* Closed the ticket

### Evidence

<img width="1920" height="1040" alt="SS02-Ticket-Resolution-and-Closure" src="https://github.com/user-attachments/assets/827c297e-c8d2-413a-bd59-170fdc62e85a" />

---

## Activity 3 — Escalation Practice

### Objective

Understand when and how a Help Desk technician should escalate an issue.

### Scenario

A user could not access a financial database. Basic credential troubleshooting and network checks had already been completed.

### Escalation Decision

The issue was escalated because Level 1 troubleshooting had been exhausted and the problem required access to a specialized business-critical database system.

### Escalation Details

* **Affected System:** Financial Database (FinDB)
* **User Account:** ADAM001
* **Required Access:** Read-only
* **Escalation Team:** Database Administration / Database Support
* **Information Provided:** User account, required access level, affected system, and reason for escalation

### Evidence



<img width="1920" height="993" alt="SS03-Ticket-Escalation" src="https://github.com/user-attachments/assets/896f6e05-0698-4d1e-bdad-ddfc2e627522" />

---


## Ticket Workflow

```text
User Reports Issue
        ↓
Create Ticket
        ↓
Categorize & Prioritize
        ↓
Troubleshoot
        ↓
      ┌───────────────┐
      │ Resolved?     │
      └───────┬───────┘
          Yes │ No
              │
        ↓     ↓
     Resolve  Escalate
        ↓     ↓
   Confirm    Specialized
   Resolution   Team
        ↓
      Close
```

## Outcome

Completed a simulated Help Desk ticket lifecycle covering **ticket creation, resolution/closure, and escalation** using Spiceworks Cloud Help Desk.














