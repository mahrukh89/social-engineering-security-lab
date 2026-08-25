# 02 — Payload Script Creation

Writing the target-side listener script (`victim.py`) that models an unauthenticated sync receiver — the piece that stands in for the trust gap behind CVE-2025-55177.

| File | Description |
|---|---|
| `01-opening-nano-editor.png` | Opening `nano victim.py` on the attacker (Kali) machine to begin writing the script |
| `02-victim-py-source-code.png` | Full source of `victim.py` — a simple TCP listener that accepts a connection and prints whatever it receives, with no verification of the sender |

**Why this step matters:** the script's simplicity is the point — it accepts data without checking who sent it, which is exactly the root cause the real CVE describes.
