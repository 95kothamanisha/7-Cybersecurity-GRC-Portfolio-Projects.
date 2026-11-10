# Study and Interview Guide — 7 GRC Projects

## Learn these 10 terms first
**Asset:** something valuable. **Threat:** possible cause of harm. **Vulnerability:** weakness. **Risk:** possible loss due to a threat affecting an asset. **Likelihood:** chance of occurrence. **Impact:** severity. **Control:** safeguard or process. **Evidence:** verifiable support. **Gap:** missing/ineffective requirement. **Remediation:** improvement action.

## 1. Mini Compliance Program
Start with assets, scope and selected ISO Annex A controls. Understand what each control expects, who owns it, what evidence demonstrates it and what gap remains. Example: A.5.18 access rights — missing periodic review → action: certify access quarterly. Don't claim the whole ISO 27001 standard is covered.

## 2. Risk Register
Score inherent risk with Likelihood × Impact, based on stated assumptions. Example laptop malware 4 × 4 = 16, Critical on this portfolio's scale. Treatment: EDR, patching, training. Residual risk is only rated after assessing control effectiveness.

## 3. Third-Party Assessment
Identify supplier criticality, ask 25 questions across five domains, request proof, score verified answers and document decision. Unknown is not automatically zero. A questionnaire alone is not vendor approval.

## 4. Incident Response
Know the incident lifecycle and role responsibilities. Rehearse the simulated phishing timeline: report, triage, session revocation, investigation, communication, recovery and lessons learned.

## 5. SOC 2 Mapping
SOC 2 criteria are broader than AWS settings. Map logical access, monitoring, change management and vendor risk to cloud configuration and organizational processes. Validate with your own screenshots; no evidence is supplied in this portfolio.

## 6. Dashboard
Explain control coverage, risk distribution and open remediation. Understand formulas and limitations: a chart doesn't establish compliance. Practice changing a status and observing the updated count.

## 7. Internal Audit
State audit objective, scope, criteria, sampling, evidence, findings and corrective actions. These are simulated examples, not verified audit nonconformities. Explain how you'd verify closure with objective evidence.

## Suggested study order (about 2 hours per first pass)
15 min scope/assets → 20 min risks → 20 min controls → 15 min vendor review → 15 min incident response → 15 min SOC 2 mapping → 10 min dashboard → 10 min audit.

## Practice questions
1. What is the difference between a threat, vulnerability and risk?
2. Why is evidence necessary for control validation?
3. How do you distinguish inherent and residual risk?
4. What happens if a vendor does not answer a critical security question?
5. What is the difference between a security incident and an audit finding?
6. Can a mapped AWS feature prove SOC 2 compliance by itself? Why not?
7. What does a GRC dashboard tell management, and what can it not tell them?
8. How would you verify that a corrective action is closed?
