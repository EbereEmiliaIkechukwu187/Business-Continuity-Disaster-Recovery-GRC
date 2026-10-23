# Business-Continuity-Disaster-Recovery-GRC
Scenario-based Business Continuity and Disaster Recovery(BCDR) assessment covering business impact analysis, risk management, RTO/RPO, recovery planning, backup strategy, incident response and tabletop testing. 
## Project Overview

As part of my Governance, Risk, and Compliance (GRC) learning journey at the International Cybersecurity and Digital Forensics Academy (ICDFA), I worked on a Business Continuity and Disaster Recovery (BCDR) scenario involving a fictional educational institution, Northbridge Skills Institute.

The scenario focused on how an organisation can continue delivering essential services when flooding and a power failure make its main site inaccessible and disrupt local IT systems.

I approached this assessment from both a business and technology risk perspective. My goal was to understand how an organization can prioritize critical services, minimize downtime, protect important data and coordinate recovery activities during a disruption.

## The Problem

The disruption affected several essential functions, including:

- Teaching and examinations
- Student fee processing
- Admissions and registration
- Staff payroll
- Records and certificate management

The situation was more challenging because some activities had strict deadlines. An examination was scheduled for 11:00 on the day of the incident, while finance and admissions activities also had same-day deadlines.

The scenario highlighted an important lesson for me: restoring IT systems is not enough. An organisation must also have practical arrangements to keep essential services running while recovery is taking place.

## What I Worked On

### 1. Business Impact Analysis (BIA)

I assessed the five business functions based on their urgency, potential disruption costs, deadlines and technical dependencies.

I also calculated the estimated financial impact of an eight-hour and a 24-hour disruption using the figures supplied in the scenario.

This helped demonstrate why recovery priorities should be based on business impact rather than simply restoring systems in the order they failed.

### 2. Recovery Objectives and Backup Strategy

I developed proposed Recovery Time Objectives (RTOs), Recovery Point Objectives (RPOs) and Maximum Tolerable Downtime (MTD) targets for the five functions.

I reviewed the available backup checkpoints and considered the risks associated with older backups, failed incremental backup chain  and shared administrator access between production and backup environments.

I also explored improvements such as independent backup credentials, multifactor authentication, protected offsite copies, regular integrity checks and documented restoration tests.

### 3. Disaster Recovery Options and Budget

I compared cold, warm and hot recovery arrangements, taking account of their estimated costs, recovery times and potential data-loss windows.

Based on the scenario's budget, I recommended the warm recovery option as an initial planning choice. However, I recognised that this option would still require improved backup protection and tested continuity arrangements to meet all the proposed recovery objectives.

This exercise helped me understand that the cheapest option is not necessarily the most suitable and the most expensive option is not automatically sufficient without proper testing.

### 4. Business Continuity and Disaster Recovery Planning

I developed a coordinated response approach covering:

- Incident activation and responsibilities
- A RACI matrix for accountability
- Temporary operating procedures for affected business functions
- A technical recovery runbook
- Communication with learners, staff, management, and relevant service providers
- Security checks before restored systems are returned to use

I also considered how the institute could manage the examination when its temporary facility had fewer workstations than the number of learners requiring them.

This showed me why continuity plans must address people, facilities, communication, and business processes alongside technology.

### 5. Recovery Scheduling and Tabletop Exercise

I prepared a recovery schedule for a two-technician team, taking account of system dependencies and tasks that could be completed in parallel.

The modelled schedule estimated that the Learning Management System (LMS) could be restored at 11:45, which was within the proposed four-hour RTO but after the examination's scheduled start time.

I also considered additional challenges, including a five-day site closure, insufficient workstation capacity, a failed database backup integrity check, suspicious backup administrator activity, and missing payment records.

These scenarios helped me appreciate the importance of decision-making, escalation, evidence preservation, and alternative service arrangements during an incident.

### 6. Governance, Metrics, and Continuous Improvement

Finally, I identified governance responsibilities and proposed performance indicators for monitoring recovery readiness.

These included recovery objective achievement, restoration-test coverage, corrective-action closure, staff training completion, and backup integrity success.

I also mapped the assessment activities at a high level to NIST SP 800-34 and ISO 22301 to understand how contingency planning, business continuity management, testing, and continual improvement fit together.

## Key Lessons Learned

This project strengthened my understanding of several important GRC concepts:

- **Business impact drives recovery priorities:** Critical services and deadlines should guide recovery decisions.
- **Backups must be tested:** A backup is only useful when it can be accessed, restored and validated.
- **Technology recovery and business recovery are different:** A system may be available while the organisation still lacks the capacity or controls to resume normal operations.
- **Clear accountability matters:** Defined roles help teams make decisions and avoid confusion during a disruption.
- **Security must remain part of recovery:** Suspicious activity or failed integrity checks should be investigated before affected backups are trusted.
- **Continuous improvement is essential:** Exercises, measurable targets and corrective actions help identify weaknesses before a real incident occurs.

## Skills Demonstrated

- Business Impact Analysis (BIA)
- Business Continuity Planning (BCP)
- Disaster Recovery Planning (DRP)
- Risk assessment and impact analysis
- RTO, RPO, and MTD development
- Backup and recovery risk assessment
- Recovery dependency mapping and scheduling
- RACI matrix development
- Incident response coordination
- Tabletop exercise planning
- KPI development and governance reporting
- Familiarity with NIST SP 800-34 and ISO 22301 concepts

## Frameworks and References

- NIST SP 800-34 Rev. 1 — *Contingency Planning Guide for Federal Information Systems*
- ISO 22301:2019 — *Security and resilience: Business continuity management systems — Requirements*
- ICDFA GRC205 — *Incident Management and Business Continuity assignment materials*

## Project Status and Disclaimer

This is an academic, scenario-based GRC project completed as part of my professional learning. The recovery schedule, proposed targets, costs and recommendations are based on the fictional scenario and are not the results of a live disaster recovery test or a production implementation.

The project reflects my ongoing interest in technology risk, cyber GRC, business continuity and operational resilience.
