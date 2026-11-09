# Severity Rating

Rate every finding with the same method so reports are comparable.

## Base score
Calculate a CVSS base score (v3.1 or v4.0; state which one you use and keep it consistent across the engagement). Map the score to a severity band:

| Severity | CVSS range |
|---|---|
| Critical | 9.0 – 10.0 |
| High | 7.0 – 8.9 |
| Medium | 4.0 – 6.9 |
| Low | 0.1 – 3.9 |
| Informational | 0.0 (no direct security impact) |

## Contextual adjustment
CVSS scores technical severity, not business risk. Document any adjustment and why. Consider:
- Is the asset internet-facing or internal only?
- Does it handle payments, personal data or authentication?
- Are compensating controls in place (WAF, network segmentation, MFA)?
- Is exploitation practical (public exploit, no authentication needed)?

Record the adjusted rating next to the base score, with a one-line justification.

## Remediation priority
- **Critical / High:** fix urgently; retest after the fix
- **Medium:** fix within the next planned release cycle
- **Low / Informational:** fix as part of normal hardening
