# Social Engineering Security Lab

A hands-on lab simulating social engineering-based exploitation in an **isolated, controlled environment**, built to study how attackers exploit human behavior rather than software vulnerabilities — and how organizations can detect, defend against, and recover from this class of attack.

> ⚠️ **Ethical use only.** Every technique in this lab was executed against systems and accounts I own, inside a fully isolated virtual network with no internet-facing exposure and no real targets. See [`docs/DISCLAIMER.md`](docs/DISCLAIMER.md) for full scope and terms. This project does not include any working exploit code, victim data, or ready-to-use phishing infrastructure.

## Why this project

Most breaches don't start with a zero-day — they start with a phone call, an email, or a fake login page that a person trusts. This lab was built to understand that attack surface first-hand: how a pretext is built, how a target is manipulated, and — just as importantly — what signals defenders and end users can use to catch it before damage is done.

## Lab Environment

| Component | Role |
|---|---|
| Kali Linux | Attacker system |
| Ubuntu (VM) | Target system |
| Isolated virtual network (NAT/host-only) | No external exposure |

## Objectives

- Understand how human factors (trust, urgency, authority) are exploited in real-world attacks
- Build and run a controlled social engineering scenario end-to-end
- Capture and analyze what the attack looked like from both sides
- Translate findings into concrete mitigation and awareness recommendations

## What's in this repo

- [`docs/METHODOLOGY.md`](docs/METHODOLOGY.md) — step-by-step walkthrough of the lab setup and attack scenario
- [`docs/MITIGATIONS.md`](docs/MITIGATIONS.md) — defensive controls and awareness takeaways derived from the exercise
- [`docs/DISCLAIMER.md`](docs/DISCLAIMER.md) — scope, consent, and ethical boundaries
- [`report/social-engineering.pdf`](report/social-engineering.pdf) — original detailed write-up/report
- `screenshots/` — supporting evidence from the lab (sanitized)

## Key Takeaway

Technical controls (firewalls, EDR, patching) don't stop an attack that targets a person instead of a machine. This lab reinforced that **security awareness training and simple verification habits** (e.g., "who actually sent this, and would they normally ask this way?") close a gap that no amount of network hardening can.

## Skills Demonstrated

`Social Engineering` · `Pretexting` · `Kali Linux` · `Virtual Lab Design` · `Security Awareness` · `Incident Analysis` · `Technical Documentation`

---

*This project is part of my personal cybersecurity learning portfolio. Feedback and questions are welcome via issues.*
