# Jira Service Management Lab

Jira Service Management lab simulating a real help desk environment. Covers ticket creation, triage, assignment, escalation, priority management, and resolution workflows using Jira Service Management.

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Building a Team](#building-a-team)
3. [Creating Tickets](#creating-tickets)
4. [Ticket Triage and Priority](#ticket-triage-and-priority)
5. [Assigning Tickets](#assigning-tickets)
6. [Escalating Tickets](#escalating-tickets)
7. [Resolving Tickets](#resolving-tickets)
8. [Queues and Filters](#queues-and-filters)

---

## Software Used

- Jira Service Management
- Microsoft Azure
- Active Directory Domain Services (AD DS)
- Microsoft Entra ID

---

## Environments Used

- Jira Service Management (Cloud)
- Windows Server 2022
- Azure Virtual Machine

---

## Project Overview

This lab simulates a real IT help desk environment using Jira Service Management. Tickets were created to reflect common help desk requests and incidents, then triaged, assigned to team members, escalated, and resolved following standard IT support workflows. The tickets in this lab reference tasks performed in the Active Directory and Entra ID labs to connect all three projects together.

---

## Building a Team

A team was built within the Support project to simulate a real help desk structure with Tier 1 and Tier 2 support members. Tickets were assigned to different team members based on the complexity and priority of the request.

- Team members were added to the Support project and assigned roles to simulate a real help desk team structure with Tier 1 and Tier 2 support.

![Jira Team](images/jira-team.png)

---

## Creating Tickets

Five tickets were created to simulate common help desk requests and incidents. Each ticket includes a summary, type, priority, and description reflecting real world IT support scenarios.

- Five tickets were created covering common help desk scenarios including password resets, account lockouts, access issues, new user setup, and software installation requests.

![Jira Tickets](images/jira-tickets.png)

---

## Ticket Triage and Priority

Triage involves reviewing incoming tickets and setting the correct priority based on business impact. High priority tickets like account lockouts require immediate attention as they directly prevent users from working.

- The Account Lockout ticket was triaged, set to High priority, moved to In Progress, and a comment was added documenting the initial investigation steps.

![Jira Triage](images/jira-triage.png)

---

## Assigning Tickets

Tickets are assigned to the appropriate technician based on the type of request. Assigning tickets ensures accountability and allows managers to track workload across the team.

- The Password Reset ticket was assigned to the lead technician and a comment was added documenting the resolution steps taken in Active Directory.

![Jira Assigned Password](images/jira-assigned-password.png)

- The New User Account Setup ticket was assigned to a Tier 1 support team member for Active Directory account creation.

![Jira Assigned New User](images/jira-assigned-newuser.png)

- The Software Installation Request ticket was assigned to a Tier 1 support team member for workstation software deployment.

![Jira Assigned Software](images/jira-assigned-software.png)

---

## Escalating Tickets

Some tickets require escalation to a higher tier of support when the issue is beyond the scope of Tier 1. Proper escalation documentation ensures the next technician has full context to continue working the ticket.

- The shared drive access ticket was escalated to a Tier 2 support team member with a comment documenting the reason for escalation and steps already taken.

![Jira Escalated](images/jira-escalated.png)

---

## Resolving Tickets

Tickets are resolved once the issue has been fixed and confirmed by the user. A resolution comment is added documenting exactly what was done before closing the ticket.

- The Password Reset ticket was resolved after confirming the user was able to log in successfully with the temporary password.

![Jira Resolved Password](images/jira-resolved-password.png)

- The Account Lockout ticket was resolved after unlocking the account in Active Directory and confirming the user was able to log in.

![Jira Resolved Lockout](images/jira-resolved-lockout.png)

---

## Queues and Filters

Queues allow help desk technicians to view and manage tickets based on specific criteria such as priority or assignment. This helps technicians prioritize their work and ensures no tickets are missed.

- The All Open queue was used to view all currently open tickets and their statuses across the team.

![Jira Queue Open](images/jira-queue-open.png)

- The Assigned to Me queue was used to view all tickets currently assigned and track their resolution status.

![Jira Queue Assigned](images/jira-queue-assigned.png)

---

## Challenges and Takeaways

**Challenges:**

**Takeaways:**
