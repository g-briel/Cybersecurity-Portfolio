# Incident Response Case Study: Ransomware & Phishing Triage in Healthcare

## Executive Summary
This artifact documents the analysis and triage of a critical security incident affecting a fictional United States primary-care healthcare facility. The organization experienced a coordinated ransomware attack that fully compromised business operations, encrypted critical patient data, and threatened organizational compliance posture. 

This case study evaluates the attack vector, operational impact, and strategic mitigations necessary to restore business continuity and preserve long-term workflow integrity.

## Incident Overview & Triage (The 5 W's)
* **Threat Actor:** An organized, financially motivated cybercrime group specializing in targeting critical infrastructure sectors (specifically healthcare and transportation).
* **Attack Vector:** Social Engineering via targeted phishing emails containing a malicious attachment.
* **Malware Deployed:** Encryption ransomware executable.
* **Timeline:** Tuesday morning, approximately 09:00 AM local time.
* **Impacted Assets:** Corporate endpoints, internal file systems, local medical records databases, and core software infrastructure.

## Operational Impact Analysis
The incident instantly moved the organization from a standard operational baseline to a state of crisis management:
1. **Denial of Service:** Complete loss of availability regarding critical patient records, forcing a total shutdown of business-critical operations.
2. **Extortion Threat:** Financial risk introduced via a prominent digital ransom note demanding payment in exchange for a decryption key.
3. **Regulatory Exposure:** Because the target was a healthcare provider, the compromise of patient data automatically triggers critical reporting workflows to legal authorities and federal regulatory bodies for technical assistance and compliance auditing.

## Post-Incident Strategic Recommendations

### 1. Hardening Security Posture against Phishing and Ransomware
To prevent future compromises and build systemic resilience, the organization must implement defense-in-depth controls:
* **Technical Controls:** Deploy robust Email Security Gateways (SEG) to filter malicious attachments before they reach users, and implement Endpoint Detection and Response (EDR) solutions capable of identifying and isolating ransomware execution behavior patterns.
* **Administrative Controls:** Establish mandatory, recurring phishing simulation training to increase employee security awareness and reduce the attack surface.
* **Operational Controls:** Enforce a strict **3-2-1 backup strategy** (3 copies of data, across 2 different media types, with 1 copy stored completely offline/air-gapped) to ensure files can be restored rapidly without relying on threat actors.

### 2. Strategic Positioning on Ransom Evaluation
* **Recommendation:** The organization should strongly avoid paying the ransom demand.
* **Justification:** Paying an extortion fee does not guarantee the reliable restoration of data, often marks the organization as a high-value repeat target, and financially funds further illicit cyber operations. Operational recovery should be driven strictly through clean backup restoration, coordinated closely with law enforcement and forensic incident response specialists.
