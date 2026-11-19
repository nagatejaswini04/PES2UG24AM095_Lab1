# Lab 1 – Requirements Engineering & UML Use-Case Modelling

**Student:** PES2UG24AM095  
**Section:** 5B  
**Assigned problem:** Problem Statement #16 – Remote Patient Vitals Alert & Monitoring App

## Scenario
A continuous monitoring application for post-operative patients that ingests SpO2, heart-rate and blood-pressure telemetry, detects configured threshold breaches, and escalates emergency alerts through a caregiver matrix.

## Contents
- `Requirements_Table.xlsx` – exactly five functional requirements and two non-functional requirements, including the two supplied sample requirements.
- `Requirements_Specification.docx` – formatted requirements specification.
- `Use_Case_Diagram.pdf` – UML use-case diagram with actors and include/extend relationships.
- `Use_Case_Flow.docx` – preconditions, main success scenario, alternate flow and postconditions.

## Important design assumptions
- A Monitoring Device is modelled as an external actor that supplies telemetry.
- A Clinical Administrator is included as an administrative actor to satisfy the handout's minimum of three actors; the assigned scenario explicitly names the Remote Patient and On-Call Caregiver as primary stakeholders.
- Clinical thresholds and caregiver response windows are configurable by an authorised care provider and are not invented as medical guidance.
- The alert escalation sequence is a software workflow proposal and should be confirmed against the instructor's detailed scenario requirements.

## GitHub
Create a separate public repository named `PES2UG24AM095_Lab1`, then upload the contents of this folder. This package does not create or publish a GitHub repository automatically.
