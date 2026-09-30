### Eldar Erik uulu

Network Technician at Pacific Lutheran University IT (since Dec 2023) · B.S. Computer Science, PLU, expected May 2027 · CompTIA Network+ · Tacoma, WA

Building things where the claims are checked against data, not asserted. Everything below is a personal or lab project unless it says otherwise — no employer configs or data.

**Infrastructure & security**
- [`MC-ZTM`](https://github.com/eldarttyy/MC-ZTM) — multi-cloud zero-trust landing zone in Terraform (AWS / Azure / GCP, default-deny, flow logs, no static credentials), plus a PowerShell 7 / Microsoft Graph script that audits Entra ID for single-factor users and unprotected admins.
- [`FirewallPolicyAsCode`](https://github.com/eldarttyy/FirewallPolicyAsCode) — a firewall rule base as reviewable YAML: linter, waivers, broadening diff, OPNsense render.
- [`ndr-lab`](https://github.com/eldarttyy/ndr-lab) — homelab Suricata + Zeek detection on a SPAN port, with detections compiled from the firewall policy.
- [`network-deployment-labs`](https://github.com/eldarttyy/network-deployment-labs) — ZTP, Ansible automation, Prometheus/SNMP monitoring, fiber loss budgets, BGP + BFD multi-site failover, PoE budgets.

**Network automation & wireless**
- [`ekahau-extract`](https://github.com/eldarttyy/ekahau-extract) — reads Ekahau survey projects from the CLI: AP inventory, channel plan, coverage scoring, design-vs-deployed drift. 99 tests, no runtime dependencies.
- [`JunosConfigGenerator`](https://github.com/eldarttyy/JunosConfigGenerator) / [`AutomatedCampusNetworkHealth`](https://github.com/eldarttyy/AutomatedCampusNetworkHealth) — network automation with commit-confirmed rollback and simulated hardware, so it runs end to end without touching production gear.

**Language & AI**
- [`kgvoice`](https://github.com/eldarttyy/kgvoice) — a Kyrgyz phonology/G2P toolkit; its vowel-harmony rule is derived and verified against 14,731 corpus word-types, not just written down.
- [`kyrgyz-speech-eval-suite`](https://github.com/eldarttyy/kyrgyz-speech-eval-suite) · [`jarvis-voice-assistant`](https://github.com/eldarttyy/jarvis-voice-assistant) · [`OpenWeb`](https://github.com/eldarttyy/OpenWeb)
