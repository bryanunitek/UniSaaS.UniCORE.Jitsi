# UniSaaS.UniCORE.Jitsi

**SCAFFOLD-ANCHOR repository — initial scaffold 2026-06-04.**

Full scaffolding, upstream-fork integration, and source-code work all pending a fresh dedicated kickoff arc. This initial commit exists to lock the repository's identity, licence position, and place in the UniCORE Sanity Check fleet so the work cannot be forgotten.

Author: **Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom.**
First commit: **2026-06-04 16:45 UTC.**

---

## What this repository is

`bryanunitek/UniSaaS.UniCORE.Jitsi` is the **Jitsi** family member: SaaS-deployment-shape public gift surface. Documentation today; source code at certification.

**Family purpose:** Open-source video conferencing platform. Multi-upstream: Jitsi Meet (application) + Jitsi Videobridge (SFU).

**Role in UniCORE:** Video conferencing substrate — UniCORE.GVB substrate-services consume Jitsi to deliver browser-based video meetings on SaaS deployments, with NGINX-based regional load-balancing across the multi-node fleet.

**Deployment shape:** This is the **SaaS-shape** member of the family. It tracks the same upstream codebase as [`UniCORE.Jitsi`](https://git.unitek-systems.com/UniCORE/UniCORE.Jitsi) (mirror: [GitHub](https://github.com/bryanunitek/UniCORE.Jitsi)) (on-prem shape) but carries SaaS-specific configuration, multi-tenant isolation patterns, and cloud-native deployment artefacts.

---

## Upstream

- **Upstream projects:** [jitsi-meet](https://github.com/jitsi/jitsi-meet) + [jitsi-videobridge](https://github.com/jitsi/jitsi-videobridge)
- **Upstream licence:** Apache-2.0
- **Our relationship:** Fork-and-extend. Upstream codebase consumed verbatim; our additions under CC BY 4.0.

---

## Platforms

Windows · Linux · macOS · iOS · Android

---

## Family — the four-repo pattern

- [`UniCORE.Jitsi`](https://git.unitek-systems.com/UniCORE/UniCORE.Jitsi) (mirror: [GitHub](https://github.com/bryanunitek/UniCORE.Jitsi)) — public on-prem-deployment-shape gift surface
- `bryanunitek/UniSaaS.UniCORE.Jitsi` — public SaaS-deployment-shape gift surface ← **this repo**
- `bryanunitek/UniCORE.Jitsi-Claw` (private) — on-prem-shape working repository
- `bryanunitek/UniSaaS.UniCORE.Jitsi-Claw` (private) — SaaS-shape working repository

---

## Status

**SCAFFOLD-ANCHOR** as of 2026-06-04. See [`STATUS.md`](STATUS.md).

---

## Contact

- **Public discussion:** [GitHub Discussions](https://github.com/bryanunitek/UniSaaS.UniCORE.Jitsi/discussions)
- **Private contact:** [LinkedIn — Bryan Fred](https://www.linkedin.com/in/bryan-fred-02209753/)

---

*Author: Bryan Fred, Unitek Systems Limited, Bedford, United Kingdom. Public. Given, not sold. Irrevocable.*
