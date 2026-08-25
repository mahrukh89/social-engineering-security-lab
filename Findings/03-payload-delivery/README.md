# 03 — Payload Delivery

Delivering `victim.py` from the attacker machine to the target over HTTP, and starting the listener on the target side.

| File | Description |
|---|---|
| `01-wget-download-on-target.png` | Target (Ubuntu) pulling `victim.py` from the attacker's lightweight HTTP server via `wget` — mirrors how a real payload is often delivered via a link rather than a direct file transfer |
| `02-listener-waiting-for-sync.png` | Target running `python3 victim.py`, now listening on port 9999 and waiting for an incoming "sync" connection |

**Why this step matters:** delivery over HTTP (rather than copying the file manually) keeps the scenario closer to a realistic attack chain, where a victim machine fetches something from an attacker-controlled source.
