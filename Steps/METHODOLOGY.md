# Methodology

This document walks through how the lab was built and how the scenario was executed. Replace the bracketed placeholders below with your actual steps, commands, and screenshots from your PDF report.

## 1. Lab Setup

- **Attacker machine:** Kali Linux (VM), [version/specs]
- **Target machine:** Ubuntu (VM), [version/specs]
- **Network:** Isolated host-only / NAT network — no bridge to the internet or production network
- **Tools used:** [e.g., Social-Engineer Toolkit (SET), custom scripts, etc. — list only what you actually ran]

## 2. Reconnaissance (Simulated)

Describe how a pretext would normally be built (OSINT on a target org/person) — even if simulated with fictional data rather than a real target.

- [ ] Identified a fictional "target" persona for the scenario
- [ ] Defined the pretext (e.g., IT support request, urgent account issue, etc.)
- [ ] Mapped out the attack narrative before execution

## 3. Scenario Execution

Step-by-step account of what was actually done in the lab, e.g.:

1. Crafted a simulated phishing page / email pretext on the Kali machine
2. Delivered it to the Ubuntu target VM within the isolated network
3. Captured target interaction (clicks, credentials entered into the test form, etc.)
4. Logged all traffic/interactions for later analysis

> Keep this section factual and specific — this is the part that shows real hands-on skill, not just theory.

## 4. Analysis

- What worked, and why (from a human-psychology angle — urgency, authority, trust)
- What technical artifacts were left behind (logs, network traffic, files)
- Screenshots: see `/screenshots` folder (sanitize any real usernames/IPs before committing)

## 5. Lessons Learned

Summarize 3–5 concrete insights from running this exercise, in your own words.
