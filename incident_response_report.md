# SOC Incident Response Report

## Case Information
- Case ID: PHISH-001
- Incident Type: Suspected Credential-Harvesting Phishing
- Severity: High (Potential Impact)
- Investigation Status: Training Analysis Completed
- Evidence: Simulated Email

## 1. Incident Summary
A simulated email claiming to be from IT Support instructed an employee to verify their password through an unverified external website within 30 minutes.

The email displayed multiple indicators of phishing, including impersonation, urgency, and a credential verification request.

## 2. Detection and Analysis
Indicators identified:
- Unverified sender domain: company-verify.example
- Unverified login URL: https://company-verify.example/login
- Threat of account disablement
- Request for password verification
- Impersonation of an IT support team

No live URL testing, malware analysis, or confirmation of credential theft was performed.

## 3. Containment Recommendations
- Advise the recipient not to interact with the link.
- Report and quarantine the message through approved security tools.
- Search email gateway logs for additional recipients.
- Block confirmed malicious indicators according to security policy.
- Review authentication activity if user interaction is suspected.

## 4. Eradication Recommendations
- Remove confirmed phishing messages from affected mailboxes.
- Revoke compromised sessions if credential exposure is confirmed.
- Reset affected credentials when necessary.
- Review email filtering and security controls.

## 5. Recovery Recommendations
- Verify account access and restore secure authentication.
- Require MFA where supported.
- Monitor accounts for unusual sign-in activity.
- Notify affected users through approved channels.

## 6. Lessons Learned
- Verify unexpected password requests through official support channels.
- Avoid trusting display names alone.
- Review full email headers when available.
- Improve user awareness of phishing and social engineering.

## 7. Final Assessment
Classification: Suspected phishing attempt
Risk: High potential impact
Confirmed Compromise: No evidence provided
Disposition: Simulated investigation completed

This report documents recommended response actions, not actions performed in a live environment.
