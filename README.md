# idverse-xion-hackathon
Decentralized Student Identity System built on XION


# IDVerse – A Decentralized Student Identity System

**Author:** Ezekiel Allison Perenabowei  
**School:** Federal University Otuoke  
**Email:** ezekielallisonalli@gmail.com  
**Zone:** South-South  
**Chapter:** NACOS Federal University Otuoke

---

## Project Overview

IDVerse is a decentralized digital identity system that allows Nigerian students to receive, manage, and share verified academic credentials on-chain. Built on XION’s infrastructure, IDVerse eliminates credential fraud, simplifies verification, and gives students ownership of their academic records.

---

## Problem Statement

Educational institutions and employers face serious bottlenecks with manual verification of academic records. Students are often required to submit the same credentials repeatedly, and forgery remains a challenge. There is no universal, secure identity system for verifying student status across institutions.

---

## Key Features

- Unique IDVerse ID for each student (e.g., `IDV-FUO-001`)
- Gasless onboarding via XION Meta Accounts (no wallet setup required)
- Schools issue credentials that are cryptographically signed and stored on-chain
- A verification portal for third parties to confirm student records securely
- Accessible on mobile and optimized for low-barrier entry

---

## XION Integration

IDVerse is built around XION’s key abstraction features:

- Meta Accounts: Students are assigned gasless smart accounts transparently
- Gasless UX: Schools and students interact without handling wallets or gas fees
- Web2-like Experience: XION powers seamless backend execution while the frontend remains intuitive

---

## Demo Workflow (Planned MVP)

1. Student signs up with school email.
2. Institution verifies identity and issues academic credentials.
3. Credentials are bound to a permanent IDVerse code (e.g., `IDV-FUO-001`).
4. Any external party can use the code to verify the credentials via a public portal.

---

## Repository Structure (Planned)

```
/smart-contracts    - Blockchain credential logic
/frontend            - User dashboard and verification portal
/docs                - Diagrams and system overview
```

---

## Current Status

This is a concept-stage submission developed individually for the XION x NACOS Intra-University Hackathon. Further development will follow post-hackathon, and the author is open to collaboration or mentoring opportunities.

---

## Contact

Ezekiel Allison Perenabowei  
Federal University Otuoke – NACOS Chapter  
Email: ezekielallisonalli@gmail.com
