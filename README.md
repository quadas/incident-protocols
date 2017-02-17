# Quadas P0 Protocol

This document is written for defining emergency incident (P0) management protocol.

# Roles
* Support Manager
* Incident Manager
* PDO
* System Operations
* Devops
* Product Manager
* Project Manager
* Devlopers (RD and QA)

# Incident Procedures
## Before P0 Incident
Incident cases come from two directions: 

* Users / customers
* System operation / monitoring

Cases from uses shall be recorded on Jira, and then copied to Redmine by Operations. 

Cases from system operation shall be kept track of on Redmine.

A potential emergency case or incident shall be reported to support manager by 

* Email
* BearyChat 
* Phone call - depending on its severity judged by first line support and Operations.

A case is categorized as P0 by **support manager** either the case is reported by user, or from system operation. And it shall be kept track on **Redmine** in all cases.

## On P0 incident 

When a incident case is categorized as P0, **support manager** shall inform following people and start a Skype group conference:

* Incident Manager
* System Operations
* PDO
* Product Manager
* Project Manager
* Devops

Once the Skype conference is initiated, **incident manager** and **Devops** shall start to investigate incident and invite all necessary **developers** into the conference.

**Support Manager** is responsible for coordinate the whole sessions and discussion. He is the one who start P0 and complete P0. 

**Incident manager** has **all permission** to allocate resources and call necessary people into the conference. **incident manager** shall update status to the people in conference, and on **redmine**.

**PDO** shall provide business impact analysis and communicate to users and customers to mitigate the impact cased by the incident. 

** Product manager ** shall be aware of potential design flaw that might case the incident

** Project manager ** shall be analyze impact on development

## After P0

P0 incident is called **resolved** by **support manager**.

**Support manager** shall initiate a **postmortem** meeting to analyze all cases and responses of the P0 incident.

A **Root-Cause-Analysis (RCA) report** shall be provided by **support manager** after postmortem.

## RCA Report
A RCA report shall contain following sections

* Incident history summary (by incident manager)
* Business impact analysis (by PDO)
* Service impact analysis (by incident manager)
* development schedule impact analysis (by project manager)
* Root cause (incident manager)
* Improvement Plan (project manager)
* Action items

