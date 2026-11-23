# HACKLE // CYBER INCIDENT TRIAGE

A retro-cyber daily incident response puzzle inspired by Courtdle and Hack The Box.

Analyze active security incident telemetry, inspect raw packet dumps and system event logs, request progressive tactical hints, and submit your technical diagnosis to clear the daily queue.

---

## Game Overview

Each shift presents 3 critical security incidents drawn from real-world attack vectors and penetration testing scenarios:

- **Telemetry Intercept:** Review incoming alert parameters, target IP addresses, active service ports, and raw log traces (e.g., Kerberos tickets, EDR process spawns, HTTP WAF logs).
- **Tactical Hints:** Unlock up to 3 progressive hints per case (Tactic & Intent, Log Breakdown, and a 50/50 Lifeline).
- **Technique Specification Modal:** Click the `[ ? ]` button beside any choice to study the attack definition, MITRE ATT&CK ID, and mitigation before entering your verdict.
- **Triage Feedback:** If a diagnosis is incorrect, the system provides a technical objection explaining why that attack vector does not match the observed telemetry.

---

## Visual Design & Aesthetics

- **CRT Phosphor Terminal:** Full-screen horizontal scanline raster overlay with phosphor green accents.
- **Cyber-Surveillance Reticle:** Top monitor vector art inspired by retro mass-surveillance aesthetics, binary memory dumps, and microchip bus traces.
- **Circuit Progress Indicators:** 45-degree diamond-cut circuit nodes that track verified, assisted, and flagged diagnoses.
- **Declassified Incident Dossier:** High-contrast classified field report styling with embedded raw log terminals.

---

## Tech Stack

- **Zero External Dependencies:** Built with pure vanilla HTML5, CSS3, and JavaScript.
- **Offline Ready:** Operates locally in any browser with zero network or server requirements.
- **GitHub Pages Compatible:** Structured as a standalone single-page application (`index.html`).

---

## Local Setup

To run locally on macOS or Linux:

```bash
# Clone the repository
git clone https://github.com/shrivastavaii/hackle.git
cd hackle

# Open in default browser
open index.html
```

---

## License

MIT License. Free for educational and training purposes.
