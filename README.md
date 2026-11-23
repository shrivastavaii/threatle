# THREATLE // DEEP PACKET INFILTRATION

A full-screen retro-cyber daily incident triage game inspired by Courtdle, Hack The Box, and Krillion.

Instead of sinking into the ocean like Krillion, **Threatle** sinks you deeper into the layers of a compromised enterprise network with each verified answer—from the outer perimeter firewall down into the deep zero-day root core.

---

## The Cyber Sinking Mechanic (Infiltration Depth)

As you solve each incident case, your telemetry probe sinks deeper into the architecture:

- **Layer 1: Perimeter Ingress (-1,200m)**: Outer Web Application Firewall (WAF), public DMZ, and edge services.
- **Layer 2: Intranet Subnet (-4,500m)**: Internal lateral movement, domain controllers, and Active Directory key distribution.
- **Layer 3: Host Kernel Ring 0 (-8,900m)**: Low-level memory segments, EDR evasion, and execution stack control.
- **Layer 4: Zero-Day Abyss (-12,000m)**: Complete root core compromise and air-gapped system access.

---

## Visual Design & Full-Screen Cockpit

- **Three-Panel HUD Cockpit:**
  - **Left Rail:** Interactive vertical infiltration shaft with live depth meter and illuminated network layer nodes.
  - **Center Console:** Wide retro-CRT surveillance monitor with targeting reticles, microchip bus traces, and classified dossiers.
  - **Right Rail:** Real-time simulated packet stream and threat radar indicators.
- **Authentic Retro CRT Aesthetics:** Scanline raster overlay, phosphor green glow (`#00ff66`), and monospace terminal typography.
- **Tactical Hints & Technique Specs:** 3-tier progressive hints with 50/50 lifeline and dedicated `[ ? ]` specification modal for learning MITRE ATT&CK techniques.

---

## Live Links & Local Play

- **Play Online (GitHub Pages):** [https://shrivastavaii.github.io/threatle/](https://shrivastavaii.github.io/threatle/)
- **GitHub Repository:** [https://github.com/shrivastavaii/threatle](https://github.com/shrivastavaii/threatle)

To run locally:
```bash
git clone https://github.com/shrivastavaii/threatle.git
cd threatle
open index.html
```

---

## License

MIT License. Free for educational and training use.
