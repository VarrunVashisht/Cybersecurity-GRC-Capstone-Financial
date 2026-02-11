# Enterprise Cyber Risk Register

| Risk ID | Risk Description | Asset | Likelihood | Impact | Inherent Risk | Existing Controls | Residual Risk | Risk Owner |
|-------|------------------|-------|-----------|--------|--------------|-------------------|---------------|------------|
| CR-01 | Unauthorized access to customer PII | Core Banking System | 4 | 5 | High | IAM, MFA, logging | Medium | Head of IT |
| CR-02 | Phishing leading to credential compromise | Email Systems | 5 | 4 | High | Email filtering, training | Medium | CISO |
| CR-03 | Third-party vendor data breach | Payment Processor | 3 | 5 | High | Vendor assessments | Medium | Procurement |
| CR-04 | Cloud misconfiguration exposing data | Cloud Platform | 3 | 4 | Medium | Cloud security reviews | Low | Cloud Lead |
| CR-05 | Delayed incident detection | SOC Tools | 4 | 4 | High | SIEM, alerts | Medium | SOC Manager |

## Notes
• Inherent Risk: Before controls
• Residual Risk: After controls
• High residual risks require escalation


• Likelihood: 1 (Low) – 5 (High)
• Impact: 1 (Low) – 5 (High)
• Risk Score = Likelihood × Impact
