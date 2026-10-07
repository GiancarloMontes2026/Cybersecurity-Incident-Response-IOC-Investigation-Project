# Cybersecurity Incident Response & IOC Investigation

## Overview

This project documents a hands-on Blue Team incident response lab completed as part of CodePath's Intermediate Cybersecurity (CYB102) program.

The lab focused on using Catalyst, an incident response management platform, to investigate, document, manage, and resolve a simulated cybersecurity incident. The investigation involved analyzing a phishing incident, identifying Indicators of Compromise (IOCs), researching malicious artifacts with threat intelligence tools, documenting findings, and completing post-incident analysis.

The project demonstrates a structured incident response workflow similar to processes used by Security Operations Center (SOC) and Incident Response teams.

## Objectives

The primary objectives of this lab were to:

- Create and manage cybersecurity incidents in Catalyst.
- Investigate a simulated phishing security incident.
- Document incident severity and relevant case information.
- Identify and analyze Indicators of Compromise (IOCs).
- Investigate suspicious IP addresses and file hashes.
- Use external threat intelligence sources to enrich IOCs.
- Document investigation findings and security artifacts.
- Classify artifacts as Malicious, Safe, or Unknown.
- Manage incident response tasks and workflows.
- Document resolution actions and close an incident.
- Perform post-incident analysis and document lessons learned.
- Classify security incidents based on investigation results.

## Lab Environment & Tools

The lab was conducted in an Ubuntu virtual machine with a locally configured Catalyst incident response platform.

### Tools & Technologies

- Catalyst
- VirusTotal
- AbuseIPDB
- Ubuntu Linux
- Indicators of Compromise (IOCs)
- IP Address Analysis
- File Hash Analysis
- Threat Intelligence
- Incident Documentation

## Incident Creation & Case Management

The investigation began by creating a phishing incident within Catalyst using information provided in an incident response report.

Relevant information such as the incident title, severity, description, playbook, and other case details was documented within the platform.

Catalyst served as a centralized location for organizing the investigation, tracking evidence, managing tasks, and documenting findings.

## IOC & Artifact Analysis

After creating the incident, I identified and documented security artifacts associated with the phishing activity.

Artifacts included indicators such as:

- Suspicious IP addresses
- File hashes
- Domain-related information
- Other security observables

These Indicators of Compromise were added to the incident so they could be tracked and analyzed throughout the investigation.

## Threat Intelligence Investigation

To enrich the identified IOCs, I used external threat intelligence resources including VirusTotal and AbuseIPDB.

VirusTotal was used to investigate IP addresses and file hashes for reputation information and associations with potentially malicious activity.

AbuseIPDB was used to investigate suspicious IP addresses and review information such as abuse history and previously reported activity.

The resulting threat intelligence was documented within Catalyst to provide additional context for the incident.

## Incident Classification & Documentation

After investigating the available evidence, artifacts were categorized based on the results of the analysis.

Possible classifications included:

- Malicious
- Safe
- Unknown

The lab also introduced incident classifications such as True Positive, False Positive, Indeterminate, and Duplicate.

Accurate classification helps security analysts determine whether an alert represents a genuine security incident and what response actions may be required.

## Incident Resolution

After completing the investigation, resolution information was documented within the incident.

This included reviewing the actions taken during the investigation and considering potential changes to systems, procedures, or security controls that could help prevent similar incidents.

The case was then moved to a closed status, representing completion of the incident response process.

## Lessons Learned

The final stage of the investigation focused on post-incident analysis.

A Lessons Learned review considered:

- Incident Summary
- Tactics, Techniques, and Procedures (TTPs)
- Response Effectiveness
- Areas for Improvement
- Recommended Future Changes

This stage demonstrated the importance of using completed incidents to improve future detection and response capabilities.

## Skills Demonstrated

Incident Response • SOC Operations • IOC Analysis • Threat Intelligence • Phishing Investigation • Security Event Investigation • VirusTotal • AbuseIPDB • Catalyst • IP Reputation Analysis • File Hash Analysis • Incident Classification • Case Management • Security Documentation • Post-Incident Analysis • Blue Team Security

## Incident Response Workflow

The project followed a structured investigation process:

**Create Incident → Review Evidence → Identify IOCs → Enrich IOCs → Analyze Findings → Document Evidence → Classify Incident → Resolve Case → Lessons Learned**

## Key Takeaways

This lab strengthened my understanding of the complete cybersecurity incident response lifecycle rather than focusing only on detecting suspicious activity.

It provided hands-on experience documenting and managing an investigation, analyzing indicators of compromise, enriching evidence using threat intelligence sources, classifying findings, recording resolution actions, and conducting post-incident analysis.

These activities reflect important responsibilities performed by SOC analysts and incident response teams when investigating and documenting security events.

## Disclaimer

This project was completed in an authorized educational lab environment as part of CodePath's Intermediate Cybersecurity (CYB102) program. All incidents, indicators, and investigative activities were part of a controlled training environment for educational and defensive cybersecurity purposes.
