# Cloud Security Lab Portfolio

Hands-on Microsoft Entra ID (Azure AD) security labs built in a self-managed lab tenant, documenting real configuration work, troubleshooting, and the reasoning behind each control — not just screenshots of a finished state.

Each lab builds on the last: the same tenant, test user, and logging pipeline carry through all seven labs, so the portfolio reflects how identity, access, and detection controls actually layer together in a real environment rather than seven disconnected tutorials.


📁 Entra ID Labs

#LabFocusKey Skills Demonstrated01Privileged Identity ManagementJust-in-time privileged accessEligible vs Active role assignment, MFA/approval-gated activation, PIM audit log02Conditional Access PoliciesZero Trust access controlMFA enforcement, Named Locations, risk-based sign-in policies, report-only testing03Identity Protection & Risk PoliciesIdentity threat detectionSign-in risk vs user risk, Tor-based risk simulation, risk investigation & remediation04Access ReviewsAccess governanceGroup & privileged role access reviews, auto-remediation, access creep prevention05Microsoft SentinelSIEM / threat huntingData connectors, analytics rules, KQL threat-hunting queries, Log Analytics architecture06Hybrid IdentityOn-prem ↔ cloud syncMicrosoft Entra Connect, UPN suffix migration, Password Hash Sync07Defender for IdentityHybrid threat detectionMDI sensor deployment, AD audit policy configuration, Advanced Hunting, attack simulation


🧠 What This Portfolio Demonstrates


Zero Trust architecture — Conditional Access, PIM, and Identity Protection working together as layered, adaptive controls rather than static rules
Identity governance — access reviews and least-privilege enforcement, including the auto-remediation of stale access
Detection & response — a hybrid pipeline spanning cloud sign-in logs (Sentinel/KQL) and on-premises AD activity (Defender for Identity)
Real troubleshooting — every lab includes a Challenges & How I Solved Them section documenting actual misconfigurations, portal quirks, and root-cause fixes encountered along the way (e.g. Azure Policy scoping issues, deprecated risk policies, connector setup failures)
Enterprise context — each lab explains why a control matters (compliance frameworks like ISO 27001, NIST 800-53, Cyber Essentials Plus) rather than just how to click through the portal



🛠️ Tools & Platforms Used

Microsoft Entra ID (P2) · Entra Connect · Privileged Identity Management · Conditional Access · Identity Protection · Access Reviews · Microsoft Sentinel · Microsoft Defender for Identity · Microsoft Defender portal · Azure Log Analytics · KQL · Windows Server 2022 (AD DS) · PowerShell · Tor Browser (risk simulation)


📖 How to Read This Repo

Each lab folder contains a self-contained README.md with:


Overview & Objectives — what the lab covers and why it matters
Step-by-Step Walkthrough — the actual configuration steps, with screenshots
Key Security Concepts Demonstrated
Challenges & How I Solved Them — real issues hit during the lab and how they were diagnosed and fixed
What I Learned
References — official Microsoft Learn documentation for every control used


Labs are numbered in the order they were built and are designed to be read in sequence, since later labs (05–07) depend on infrastructure established in earlier ones (02, 06).


📬 About

Built as a hands-on demonstration of enterprise identity and cloud security engineering skills, aligned with real-world Zero Trust and hybrid identity architectures.
