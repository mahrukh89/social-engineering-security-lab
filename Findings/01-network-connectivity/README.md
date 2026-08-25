# 01 — Network Connectivity

Verifying that the attacker (Kali) and target (Ubuntu) VMs can reach each other over the isolated private network before any further steps.

| File | Description |
|---|---|
| `01-kali-attacker-ip-config.png` | `ip a` output on the Kali attacker VM — confirms IP `192.168.56.102` on the isolated host-only adapter |
| `02-ubuntu-target-ip-config.png` | `ip a` output on the Ubuntu target VM — confirms IP `192.168.56.103` on the same isolated segment |

**Why this step matters:** everything after this point depends on both machines being reachable only within the lab's private network (`192.168.56.0/24`), with no route to the internet or any production system.
