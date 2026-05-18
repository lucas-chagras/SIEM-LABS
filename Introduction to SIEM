# Introduction to SIEM

This lab focused on the fundamentals of Security Information and Event Management (SIEM), including:

- Security monitoring
- Event correlation
- Alert investigation
- Log analysis
- Detection rules
- Suspicious process identification

The objective was to understand how SIEM platforms help SOC analysts identify and investigate suspicious activities within monitored environments.

---

# Lab Scenario

A suspicious activity was triggered inside the monitored environment.

The SIEM generated an alert related to a suspicious process execution, requiring investigation to determine:

- Which process generated the alert
- Which user executed the process
- Which host was involved
- Whether the alert represented malicious activity
- What detection rule triggered the alert

---

# Investigation Summary

| Investigation Item | Result |
|---|---|
| Suspicious Process | `cudominer.exe` |
| User | `chris` |
| Hostname | `HR_02` |
| Detection Rule Term | `miner` |
| Alert Classification | `True Positive` |
| Flag | `THM{000_SIEM_INTRO}` |

---

# Suspicious Process Analysis

## Process: `cudominer.exe`

The process identified during the investigation was `cudominer.exe`.

This process name strongly suggests cryptocurrency mining activity.

Possible indicators:

- Unauthorized resource usage
- Cryptomining malware
- High CPU utilization
- Persistence mechanisms
- Potential compromise

---

# User Investigation

## User: `chris`

The SIEM logs identified the user responsible for executing the suspicious process.

Monitoring user activity is essential because it helps:

- Detect compromised accounts
- Identify insider threats
- Track malicious execution
- Correlate suspicious behavior

---

# Host Investigation

## Host: `HR_02`

The suspicious activity originated from the host `HR_02`.

Host analysis is critical for:

- Containment actions
- Isolation procedures
- Malware investigation
- Endpoint visibility

---

# Detection Rule Analysis

## Rule Term: `miner`

The SIEM detection rule matched the term `miner`, indicating suspicious mining-related behavior.

Examples of monitored miner-related activity:

- Cryptomining processes
- Mining pools communication
- Resource abuse
- Unauthorized execution

---

# Alert Classification

## Classification: True Positive

The event was classified as a True Positive because the activity represented legitimate suspicious behavior requiring investigation and response.

This classification indicates:

- The alert was accurate
- Malicious or unauthorized behavior was detected
- Further response actions would be necessary in a real environment

---

# Skills Practiced

- SIEM Navigation
- Alert Investigation
- Event Correlation
- Threat Identification
- Process Analysis
- Basic SOC Workflow

---

# Key Takeaways

- SIEM platforms centralize logs and alerts
- Correlation rules help identify suspicious behavior
- Proper alert classification is critical
- Endpoint visibility is essential for investigations
- Security monitoring requires contextual analysis

---

# Next Steps

- Continue SIEM labs
- Study Windows Event IDs
- Explore Wazuh and Splunk
- Learn Sigma Rules
- Practice threat hunting
