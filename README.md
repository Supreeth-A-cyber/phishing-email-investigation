# 🛡️ Phishing Email Investigation

**Email Security | Phishing Analysis | SOC Investigation**

![Focus](https://img.shields.io/badge/Focus-Blue%20Team-blue)
![Project](https://img.shields.io/badge/Project-SOC%20Case%20Study-purple)
![Status](https://img.shields.io/badge/Status-Training%20Scenario-orange)

## 📌 Project Overview

This project demonstrates a structured, evidence-based approach to investigating a suspected phishing email. It uses a fictional training scenario to practice identifying suspicious indicators, documenting evidence, evaluating uncertainty, and recommending defensive actions.

## 🎯 Objectives

- Identify common phishing indicators.
- Review sender and reply-to address discrepancies.
- Assess suspicious links without visiting them.
- Document evidence, limitations, and unknowns.
- Produce a preliminary SOC analyst verdict.

## 🧰 Skills Demonstrated

- Phishing email triage
- Indicator of Compromise (IOC) review
- Email authentication concepts: SPF, DKIM, and DMARC
- Evidence-based risk assessment
- Incident documentation and defensive recommendations

## 📁 Project Structure

```text
phishing-email-investigation/
├── README.md
├── case-report.md
└── indicator-analysis.md
```

## 🔍 Investigation Summary

The fictional email claims that the recipient's mailbox will be suspended unless they verify their account. The scenario includes urgent wording, differing sender and reply-to addresses, and a verification link.

**Preliminary assessment:** Suspicious — further investigation required.

The available information does not establish malicious intent, credential theft, or account compromise. Actual email headers, authentication results, and relevant security logs would be needed for further validation.

## 📄 Investigation Documents

- [Case Report](case-report.md) — scenario, observations, initial assessment, and SOC verdict.
- [Indicator Analysis](indicator-analysis.md) — indicator review, evidence limitations, and recommended defensive checks.
- [SOC Triage Decision](triage-decision.md) — triage observations, disposition criteria, next investigative steps, and evidence-based reasoning.

## 🔒 Safety and Limitations

This is a fictional educational case study. The domains and indicators are for documentation only. No live suspicious URLs were visited, and no real email or account was investigated.

A suspicious indicator is not proof of compromise. All conclusions are limited to the evidence available in the scenario.
