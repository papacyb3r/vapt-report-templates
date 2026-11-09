# Rules of Engagement Checklist

Complete and sign off before any testing begins.

## Authorisation
- [ ] Written authorisation from an authorised representative of the asset owner
- [ ] Third-party hosts (cloud, SaaS, CDN) confirmed as in scope or excluded, with provider policy checked
- [ ] Legal and contractual terms (NDA, liability) in place

## Scope
- [ ] In-scope assets listed: <URLs / IP ranges / app builds / APIs>
- [ ] Out-of-scope assets listed explicitly
- [ ] Test type: black box / grey box / white box
- [ ] Test accounts and roles provided (list roles, not credentials)
- [ ] Environment: production / UAT / staging

## Constraints
- [ ] Testing window: <start – end, timezone>
- [ ] Rate limits and prohibited techniques (e.g. denial of service, social engineering, destructive payloads)
- [ ] Data handling: no extraction of real customer data beyond proof of access
- [ ] Source IPs the testers will use

## Communication
- [ ] Primary and emergency contacts on both sides
- [ ] Process for reporting critical findings immediately
- [ ] Agreed report format, delivery date and retest terms

## Close-out
- [ ] Test accounts and artefacts removed
- [ ] Evidence stored securely, retention period agreed
