# Phishing Email Investigation — Case 001

## 1. Case Overview

- **Case ID:** PHISH-001
- **Investigation Type:** Suspected phishing email
- **Environment:** Fictional training scenario
- **Analyst:** Junior SOC Analyst
- **Status:** Initial assessment
- **Severity:** To be determined after analysis

## 2. Scenario

A fictional employee receives an email claiming that their mailbox will be suspended unless they verify their account. The email uses urgent language and asks the recipient to follow a link.

This case is designed to practice identifying phishing indicators and documenting findings. No real email, account, or organization is involved.

## 3. Email Evidence

| Field | Observed value |
|---|---|
| Sender | `IT Support <support@company-example.invalid>` |
| Reply-To | `verify@account-check.example` |
| Subject | `Urgent: Mailbox suspension notice` |
| Displayed link text | `Verify your mailbox` |
| Example URL | `hxxps://account-check.example/verify` |
| Attachment | None specified |
| Recipient action | Unknown |

**Safety note:** The email, addresses, and URL above are fictional training indicators. The `.invalid` domain is reserved for invalid names; the other example domain is for documentation. Do not visit the example URL.

## 4. Initial Observations

- The message uses urgency to pressure the recipient into acting quickly.
- The sender claims to represent IT support, but the sender and reply-to addresses differ.
- The displayed link requests mailbox verification.
- The available scenario does not establish whether the email was delivered to a real inbox, whether the link is operational, or whether anyone clicked it.

## 5. Initial Assessment

The email has indicators consistent with a possible phishing attempt. These indicators justify further review, but they do not independently prove malicious intent.

## 6. Next Investigation Steps

1. Review the full email headers in a safe, authorized environment.
2. Compare the sender and reply-to domains with known legitimate organizational domains.
3. Examine URL indicators without opening the link.
4. Determine whether the recipient clicked the link or submitted credentials.
5. Document supporting evidence and revise the severity assessment.

## 7. Conclusion

**Preliminary result:** Suspicious — further investigation required.

No compromise is confirmed in this fictional scenario.
