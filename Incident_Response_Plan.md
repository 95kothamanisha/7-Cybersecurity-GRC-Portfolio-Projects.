# NovaCloud — Incident Response Plan (Simulation)
**Version:** 1.0 | **Owner:** Security Lead | **Review:** annually and after major incidents.

## 1. Purpose and scope
Coordinate detection, analysis, containment, eradication, recovery and lessons learned for incidents affecting NovaCloud cloud systems, users and customer data.

## 2. Roles
Incident Commander (Security Lead): severity, coordination and decisions. IT Lead: identity/endpoint containment. Engineering Lead: application investigation and restoration. Legal/Privacy: assess contractual and legal notification duties. Communications Lead: approved stakeholder updates. Executive Sponsor: major-risk decisions.

## 3. Severity
SEV1: confirmed major data compromise or business outage. SEV2: limited confirmed compromise. SEV3: suspicious event under investigation. Severity is reassessed as facts develop.

## 4. Workflow
1. **Detect and report:** preserve alert, reporter, timestamp and affected assets.
2. **Triage:** validate event, classify severity and appoint incident commander.
3. **Contain:** isolate affected accounts/devices; revoke sessions and rotate credentials where appropriate. Preserve forensic evidence.
4. **Eradicate:** remove malicious access, fix root cause and verify clean state.
5. **Recover:** restore services from trusted state, validate functionality, monitor for recurrence.
6. **Communicate:** record decisions; legal/privacy assess notification requirements based on applicable laws and contracts.
7. **Lessons learned:** conduct retrospective, assign corrective actions and track closure.

## 5. Evidence and communications
Maintain incident ticket, timeline, log exports, actions, approvals and post-incident report. Avoid sharing secrets or personal data in public repositories. Use approved internal channels for updates.

## 6. Exercise and review
Run tabletop at least annually; document participants, decisions, gaps, action owners and target dates. This document is a simulated policy, not proof of organizational adoption.
