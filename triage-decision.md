# SOC Triage Decision — Case PHISH-001

## 1. Purpose

This document records a preliminary triage decision for the fictional phishing email described in `case-report.md`.

The goal is to determine the appropriate next action based on available evidence, while clearly identifying what remains unknown.

## 2. Initial Alert

| Field | Assessment |
|---|---|
| Alert type | Suspected phishing email |
| Urgency language | Present |
| Sender and Reply-To differ | Yes |
| Account verification link | Present |
| Email authentication results | Unknown |
| Recipient clicked the link | Unknown |
| Credentials submitted | Unknown |
| Confirmed compromise | None established |

## 3. Triage Decision Table

| Observation | Analyst interpretation | Next action |
|---|---|---|
| Urgent account-verification request | Potential social-engineering indicator | Review message context and sender identity |
| Sender and Reply-To differ | Warrants validation; not proof of spoofing | Check authorized sender records and email headers |
| SPF, DKIM, or DMARC results unavailable | Sender authentication cannot yet be assessed | Obtain and review full headers |
| Link destination not verified | Link risk remains undetermined | Use approved security-analysis tools without opening the link |
| Recipient interaction unknown | Potential impact cannot be assessed | Check available mail gateway and identity logs |
| No corroborating evidence of compromise | Impact remains unconfirmed | Avoid claiming a successful attack |

## 4. Disposition Criteria

### Close as Benign

Consider closure only when sufficient evidence supports a legitimate explanation and organizational procedures permit closure.

### Continue Investigation

Continue when indicators remain suspicious but evidence is incomplete. Collect additional authorized evidence and update the case notes.

### Escalate

Escalate according to the organization's incident-response procedure when evidence supports malicious activity, potential credential exposure, or other material security risk.

## 5. Current Decision

**Disposition: Continue investigation.**

### Rationale

The fictional email contains urgency language, a mailbox-verification request, and differing sender and Reply-To addresses. These indicators justify further review, but they do not independently confirm malicious intent.

### Evidence Required Next

1. Full email headers and authentication results.
2. Validation of the sender and Reply-To addresses.
3. Approved analysis of the link destination and reputation.
4. Mail gateway, click, and identity logs, where available.

## 6. Analyst Notes

- **Confirmed:** The scenario includes the listed suspicious indicators.
- **Unknown:** Sender authenticity, link behavior, recipient interaction, and actual impact.
- **Not established:** Credential theft, malware execution, or account compromise.

## 7. Final Note

This is a fictional training exercise. The triage decision demonstrates evidence-based reasoning and must not be represented as a real incident investigation.
