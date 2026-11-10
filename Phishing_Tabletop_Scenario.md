# Tabletop: Phishing and Account Compromise
**Scenario:** Fictional employee receives a fake Microsoft 365 sign-in message and enters credentials. Monitoring later flags suspicious login activity. No real accounts or production systems were touched.

## Injects / facilitator prompts
- 09:00 Employee reports unusual sign-in email. What evidence is preserved?
- 09:15 Identity logs show an unfamiliar session. Who declares severity?
- 09:30 Suspicious mailbox forwarding rule is found. How do you contain without destroying evidence?
- 10:00 Customer-data access is uncertain. Who decides whether notifications are needed?
- 11:00 Credentials and sessions are revoked. What validates recovery?

## Expected actions
Open incident ticket, identify affected identity, preserve logs, revoke sessions, reset credentials, investigate mailbox rules and downstream access, review notification obligations, monitor and document lessons learned.

## Observed simulated gaps
No single incident contact list; identity log retention undocumented; tabletop cadence missing.

## Corrective actions
Publish contact roster (Security Lead, 30 days); define identity logging retention (IT Lead, 45 days); schedule annual tabletop (Security Lead, 60 days).
