# Aqua Block Crisis Detected

Critical infrastructure is under attack!

**NICE Work Roles**

- [Cyber Defense Incident Responder](https://niccs.cisa.gov/workforce-development/nice-framework)
- [Cyber Defense Analyst](https://niccs.cisa.gov/workforce-development/nice-framework)

**NICE Tasks**

- [T0041](https://niccs.cisa.gov/workforce-development/nice-framework): Coordinate and provide expert technical support to enterprise-wide cyber defense technicians to resolve cyber defense incidents.
- [T0278](https://niccs.cisa.gov/workforce-development/nice-framework): Collect intrusion artifacts (e.g., source code, malware, Trojans) and use discovered data to enable mitigation of potential cyber defense incidents within the enterprise.
- [T0260](https://niccs.cisa.gov/workforce-development/nice-framework): Analyze identified malicious activity to determine weaknesses exploited, exploitation methods, effects on system and information.

## Background

A dam was the recent target of an advanced persistent threat (APT) group. Nothing malicious was detected…*yet*. However, employee credentials were compromised, and malware was planted on the SCADA system. Employees have attempted to remove their history, logs, and communications.

-	Investigate and find the leaked password
-	Use the leaked credentials to discover the malware on the SCADA system

A list of usernames or passwords is unavailable; but, rumors say usernames are lowercase, common first names, and passwords are username plus a couple of digits. 

## Getting Started

SCADA and supporting infrastructure are on `10.1.1.0/24` and `10.2.2.0/24`. You are authorized to enumerate, scan, and log into these systems.

Enumerate the network users, discover their credentials, understand how the credentials were leaked, gain access to the SCADA, and find the malware.

## System and Tool Credentials

| system/tool | username | password |
| ----------- | -------- | -------- |
|abcd-kali     |user    |tartans |
|securityonion (web)|admin@so.org    |tartans@1    |
|hmi (http://10.1.1.15/scada)|prescup    |6@Zkeva6N8G!    |

## Note

Attacking or unauthorized access to `challenge.us` (10.5.5.5) is forbidden. You may only use the provided web page to view challenge progress and download any challenge artifacts that are provided.

## Challenge Questions

1. What is the password that was disclosed?
2. What is the username/handle of the creator of the malware planted on the SCADA system?