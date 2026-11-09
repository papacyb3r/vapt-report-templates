# Report Structure

## Part 1: Executive Summary (2–4 pages, non-technical)
1. Purpose and scope
2. Overall risk posture in one paragraph
3. Findings by severity (table or chart)
4. Top priorities: the 3–5 issues to fix first, in business language
5. Positive observations (what is working well)
6. Recommended next steps and retest plan

## Part 2: Technical Report
1. Methodology (e.g. OWASP WSTG, OWASP ASVS, OWASP API Security Top 10, PTES) and tools used
2. Scope, environment, dates and limitations
3. Summary table of findings: ID, title, severity, affected asset, status
4. Detailed findings (one per [finding template](finding-template.md))
5. Appendices: tool output, test account roles, retest results

## Quality checks before delivery
- [ ] Every finding has reproducible steps and evidence
- [ ] Severity follows [severity rating](severity-rating.md)
- [ ] No credentials or sensitive data left in screenshots
- [ ] Remediation is specific, not generic
- [ ] Executive summary matches the technical findings
- [ ] Peer reviewed by a second consultant
