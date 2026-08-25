# 04 — Fake Sync Exploitation

Simulating the core authorization bypass: sending an unverified "sync" message from the attacker directly to the target's listener, with no linked-device authorization behind it.

| File | Description |
|---|---|
| `01-attacker-sends-unauthorized-sync.png` | Attacker using `nc` (netcat) to send the string `UNAUTHORIZED_LINKED_DEVICE_SYNC` to the target's listener on port 9999 |
| `02-target-receives-sync-payload.png` | Target's listener accepting the connection and printing the received data — with no check on where it came from |

**Why this step matters:** this is the moment that mirrors CVE-2025-55177 directly — a message is accepted and processed purely because it arrived in the expected format, not because its origin was verified.
