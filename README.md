# ServiceNow Ticketing Home Lab (Incident Management)

## 🧩 Objective
Demonstrate understanding of basic ServiceNow ticket navigation and incident-management workflow by creating, triaging, documenting, and resolving a sample incident.

## 🎯 Scenario
A user is locked out of their account after multiple failed login attempts. The goal is to log the incident, investigate using knowledge/related search, perform account recovery steps, document actions, and close the ticket with proper resolution notes.

## 🧠 Skills Practiced
- Incident creation and field navigation (Caller, Short Description, Urgency, State)
- Using Related Search Results / Knowledge suggestions
- User record navigation (sys_user)
- Work Notes documentation + Activity tracking for audit trail
- Resolution codes/notes and SLA awareness

## 🧰 Tools Used
- ServiceNow Personal Developer Instance (PDI)
- Incident module
- Knowledge & Related Search
- User table (sys_user)
- SLA section (review/awareness)

---

## 🪜 Steps Performed

### 1) Provisioned ServiceNow PDI + verified instance version
Confirmed instance status/version (Yokohama) and logged in with admin access.
![PDI Setup](images/Servicenow1.png)

### 2) Created an Incident for “Password Lockout”
Logged the incident, selected a Caller, and entered a clear Short Description. Used Related Search Results / Knowledge suggestions to guide next steps.
![Incident Created](images/Servicenow2.png)

### 3) Triaged the Incident (Urgency/State)
Reviewed key fields and set the incident status appropriately to begin investigation and resolution.
![Incident Triage](images/Servicenow3.png)

### 4) Created/Reviewed the User record (sys_user)
Created/updated the user profile to support account recovery and prepare for password reset actions.
![User Record](images/Servicenow4.png)

### 5) Documented troubleshooting in Work Notes + reviewed Activity
Added internal Work Notes and confirmed updates/field changes were captured for traceability and handoff readiness.
![Work Notes](images/Servicenow5.png)

### 6) Resolved + closed the Incident with resolution notes and SLA awareness
Closed the ticket with a Resolution Code and clear Resolution Notes, then reviewed SLA details to demonstrate awareness of time targets.
![Resolution + SLA](images/Servicenow6.png)

---

## ✅ Outcome
Successfully demonstrated the ability to navigate ServiceNow, create and manage an incident through its lifecycle, document troubleshooting steps, and close the ticket with proper resolution notes and SLA awareness.

## 🔁 Next Improvements
- Add categorization (Category/Subcategory) and Assignment Group routing
- Create a short Knowledge Base article for “Password Lockout” and link it to the incident
- Build a simple report/dashboard showing incidents by state/priority
