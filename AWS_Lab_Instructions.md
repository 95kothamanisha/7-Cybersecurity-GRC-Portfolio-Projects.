# AWS Lab: SOC 2 Control Mapping
**Scope:** conceptual mapping of selected AICPA Trust Services Criteria to AWS features. Criteria are **paraphrased**; consult licensed/current authoritative criteria for formal audit use. Mapping alone is not SOC 2 compliance or a SOC 2 report.

## Before starting
Use a personal sandbox account, MFA, billing alerts and least privilege. Do not upload account IDs, access keys, secrets, personal data or unredacted configuration screenshots to GitHub.

## Safe hands-on validation
1. **IAM / MFA:** check root account MFA and admin user access; capture a redacted settings screenshot.
2. **Logging:** inspect whether CloudTrail is configured; record scope, retention and destinations. Enabling features may incur cost.
3. **S3 encryption:** inspect default encryption and block-public-access settings of a test bucket. Never use real customer data.
4. **Network:** review test security-group inbound rules; document why each is necessary.
5. **Monitoring:** inspect CloudWatch alarms / relevant detections; capture redacted evidence.
6. **Change management:** document a sample approved pull request and review trail.

## Evidence protocol
For each mapped control: screenshot filename, timestamp, account/environment (redacted), configuration observed, reviewer conclusion and gap. Mark 'Not tested' until you personally verify it.

## Interpretation
Cloud settings may support control objectives, but operating effectiveness and organizational processes require additional evidence. Do not claim an external SOC 2 audit was performed.
