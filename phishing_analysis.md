# Phishing Email Investigation Report

## Case Information
- Case ID: PHISH-001
- Investigation Type: Phishing / Credential Harvesting
- Evidence Type: Simulated Email
- Analyst Role: SOC Analyst (Training Lab)
- Risk Assessment: High (Potential Impact)

## 1. Investigation Overview
A simulated email impersonating an IT support team was reviewed for potential phishing activity. The message requested that an employee verify their password through an external login link within 30 minutes.

## 2. Email Evidence
- Display Name: IT Support
- Sender: security@company-verify.example
- Recipient: employee@company.example
- Subject: URGENT: Your Account Will Be Disabled
- Suspicious URL: https://company-verify.example/login

All domains are fictional training examples.

## 3. Suspicious Indicators
1. Sender impersonation: The display name claims to be IT Support, but the sender domain is not independently verified as an authorized company domain.
2. Urgency: The email threatens account disablement within 30 minutes.
3. Credential harvesting: The message directs the recipient to a login page to verify a password.
4. Suspicious URL: The external login link is not verified as an official company authentication page.
5. Social engineering: The message uses fear of account loss to pressure the recipient.

## 4. Email Header Analysis
Only the displayed sender, recipient, subject, and date are available in the simulated evidence.
Full email headers, including Received, SPF, DKIM, and DMARC results, were not provided. Authentication failure or spoofing cannot be confirmed from this sample alone.

## 5. Risk Assessment
Risk Level: High (Potential Impact)

The email is consistent with a credential-harvesting phishing attempt. Actual credential theft, malicious website behavior, and account compromise have not been confirmed.

## 6. Recommended Response
- Do not click the suspicious link or submit credentials.
- Report the message to the security team.
- Verify the request through an established IT support channel.
- Review email gateway logs and available authentication results.
- Block confirmed malicious indicators under organizational policy.
- If credentials were submitted, reset the password, revoke active sessions, and review account sign-in activity.

## 7. Investigation Conclusion
The simulated email contains multiple phishing indicators, including urgency, IT support impersonation, and a request to verify credentials through an unverified external link.

Disposition: Suspected credential-harvesting phishing attempt.
Status: Training investigation completed.
