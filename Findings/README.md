# 05 — Fake URL Exploitation

Extending the previous step to mirror the specific real-world impact in CVE-2025-55177: an unauthorized sync message causing arbitrary URL content to be processed.

| File | Description |
|---|---|
| `01-attacker-sends-fake-url.png` | Attacker using `nc` to send `http://malicious.example.com/fake-sync` to the target's listener |
| `02-target-receives-fake-url.png` | Target's listener receiving and printing the fake URL — again, with no verification step |

**Note:** `malicious.example.com` uses the IANA-reserved `example.com` domain. No real or resolvable domain was contacted at any point in this lab.

**Why this step matters:** this shows the practical consequence of the authorization gap — not just "a message was accepted," but that the accepted message can contain a URL a real system might go on to process automatically.
