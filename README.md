# Arety RCB — Public Documentation

This repository hosts the public architecture documentation for **Real Cognition Brain (RCB)** and the versioned technical documentation for the **Arety RCB 1.2** served configuration.

- Architecture documentation: https://documentation.arety.cloud
- **RCB 1.2 technical site:** https://documentation.arety.cloud/rcb-1.2/
- Public service: https://tests.arety.cloud
- Developer guide: https://tests.arety.cloud/developers

## Documentation versions

- The root site describes the RCB architecture and earlier model history.
- `/rcb-1.2/` documents the RCB 1.2 configuration, its nine-node layout, thought lifecycle, intent routing, comparison modes, memory and knowledge stores, public interfaces, measured evidence, limitations and responsible-use notes.

## Terminology

- **RCB** is the architecture; it has no version number.
- **RVTCB** is the software package implementing RCB with virtual nodes (0.1.x; protocol `rvtcb/0.1`).
- **RPTCB** refers to an implementation using physical nodes.
- **Arety RCB 1.2** is a served configuration identified by `arety-rcb-1.2`.

## Evidence and scope

The RCB 1.2 documentation follows the technical whitepaper v3 dated 2026-10-26. Benchmarks are small, author-designed evaluations on stated tasks and hardware; they are not general intelligence evaluations. Known defects and unimplemented design directions are explicitly labelled.

The RCB 1.2 page is a static HTML site and requires no build step or JavaScript framework.

## Hosting

The repository's existing GitHub Pages custom domain is `documentation.arety.cloud`. The RCB 1.2 site is published as a versioned subdirectory at `/rcb-1.2/`, leaving the existing root documentation intact.

---
Made by Arety.
