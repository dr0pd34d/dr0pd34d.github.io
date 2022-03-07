---
layout: post
title:  "Zero-Point Security - Red Team Operator Lab + Certification"
date:   2022-02-20 20:00:00 +0100
categories: Certification Lab RedTeam
---

> Red Team Ops is an **online course** that teaches the basic principals, tools and techniques, that are synonymous with **red teaming**.<br />
Students will first cover the core concepts of adversary simulation, command & control, and how to plan an engagement.  They will then learn about each stage of the attack lifecycle from initial compromise, to full domain takeover, data hunting, and data exfiltration.  Students will also take various OPSEC concerns into account and learn how to bypass defences such as Windows Defender, AMSI and AppLocker.  Finally, they will cover reporting and post-engagement activities.

**Source:** [Red Team Operator Course][red-team-ops-course]

| ⚠️ WARNING          |
|:---------------------------|
| This blog post should summarize my experience with the course and exam.<br />All content is displayed in my own opinion and can vary from person to person.|


## Course

The course as of today includes the following topics:
- Course introduction
- Command & Control
- External Reconnaissance
- Initial Compromise
- Host Reconnaissance
- Host Persistence
- Host Privilege Escalation
- Domain Reconnaissance
- Lateral Movement
- Credentials & User Impersonation
- Password Cracking Hints & Tips
- Session Passing
- Pivoting
- Data Protection API
- Kerberos
- Active Directory Certificate Services
- Group Policy
- Discretionary Access Control Lists
- MS SQL Servers
- Domain Dominance
- Forest & Domain Trusts
- Local Administrator Password Solution
- Bypassing Defences
- Data Hunting & Exfiltration
- Post-Engagement & Reporting
- Extending Cobalt Strike

## Lab

The lab is provided as a virtual environment through the provider [SnapLabs][snaplabs-overview].<br />
It can be started and stopped in a matter of minutes to use the lab hours efficiently.<br />
The access to the lab is provided via a web browser and the use of Apache Guacamole as the remote desktop solution.<br />
Sometimes copy paste was a hit or miss for me and the performance was good as long as the internet connection is stable.

## Exam

The exam has a lab time of 48 hours which can be used throughout 4 days in total.<br />
To pass the exam, **6 out of 8 flags** have to be collected.<br />
There is no report needed and I really enjoyed the chain in the exam and would have loved to continue in another environment.<br />
In my case I was able to collect all 8 flags within 13 hours.<br />
As soon as the 4 day time frame is over, the **flags are automatically checked** and if correct generate and send you your badge.

![Alt text](/assets/images/zp-coin-red-100.png)

## Pricing

| £365.00	| Course Only					|
| £399.00	| Course + 40 hour lab bundle	|

RastaMouse did an amazing job to make the course even more accessible to someone investing private money by recently adding payment options that include splitting the payment into 4 separate payments.

| 4 x £91.25	| Course Only					|
| 4 x £99.75	| Course + 40 hour lab bundle	|

## Final verdict

If you are willing to learn and grow in the area of red teaming, I highly recommend this course and certification.<br />
I had prior infrastructure assessment and active directory experience which made the course a bit easier.<br />

**But as the course page states:**
> The most successful students are not those with the greater technical knowledge - but those with a passion for learning new skills, solving problems, have great resilience and fortitude!

<!-- Links -->
[red-team-ops-course]: https://courses.zeropointsecurity.co.uk/courses/red-team-ops
[snaplabs-overview]: https://www.snaplabs.io/