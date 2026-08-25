# Mitigations & Defensive Takeaways

Findings from this lab, translated into practical defenses. This is the section that shows you're thinking like a defender, not just an attacker — it's usually what makes a social engineering project credible on a portfolio.

## User-Level Controls

- Security awareness training focused on recognizing urgency/authority pressure tactics
- Verification habits: confirming unusual requests through a second channel (e.g., calling back a known number, not one provided in the suspicious message)
- Phishing simulation programs to measure and improve click-through rates over time

## Technical Controls

- Email filtering / anti-phishing gateways (SPF, DKIM, DMARC enforcement)
- Multi-factor authentication to reduce impact of credential capture
- Endpoint monitoring for anomalous login behavior following a suspected social engineering event
- Network segmentation to limit lateral movement if a single user is compromised

## Organizational Controls

- Clear, easy incident-reporting process so employees report suspicious contact without fear of blame
- Regular tabletop exercises simulating social engineering incidents
- Least-privilege access so a single compromised account has limited blast radius

## Summary

No single control stops social engineering — it's a layered combination of trained people, verification habits, and technical safety nets that catches what the other layers miss.
