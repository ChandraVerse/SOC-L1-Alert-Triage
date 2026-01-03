# SOC-L1-Alert-Triage

# 🛡️ SOC L1 Alert Triage (TryHackMe) — Lab Notes

Hands-on completion notes for the TryHackMe: SOC L1 Alert Triage room, focused on building a repeatable Tier-1 workflow to review, investigate, classify, and close SOC alerts.  
This lab uses a simulated SOC dashboard/SIEM experience and walks through alert properties, prioritization, and triage lifecycle.

---

## 📌 Room Info
- Platform: TryHackMe (SOC Level 1 path)  
- Room: SOC L1 Alert Triage  
- Key objectives covered: alert concept, alert fields/status/classification, L1 triage process, and practicing SOC workflows.

---

## 🎯 What was practiced
- Understanding alert **properties** (time, name, severity, status, verdict/classification, assignee, description, and alert fields such as host/user/IP/commandline).  
- Alert prioritization strategy: filter unseen/unresolved alerts, sort by severity, and avoid taking work already handled by other analysts.  
- L1 responsibilities: review alerts, separate true threats vs noise, and escalate to L2 when needed.

---

## 🔄 Triage workflow followed
Based on the room’s triage flow, the lab followed this end-to-end sequence:  
1. Prioritize alerts and select the first actionable one.  
2. Assign the alert to yourself and set status to In Progress to take ownership. 
3. Read alert name/description and capture key entities (host, IP, user).  
4. If a workbook/playbook exists, follow it; otherwise investigate directly in SIEM/EDR logs.  
5. Investigate surrounding activity (before/after the alert), validate with context/threat intel if required, and reach a verdict (True Positive / False Positive).  
6. Decide whether to escalate to L2; if not, document findings, then move the alert to Closed.

---
