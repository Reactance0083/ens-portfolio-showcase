# ENS & Digital Identity Portfolio

**C. Wade Allen | Blockchain, workflow design, and AI-assisted implementation**

A public case study of an independently held ENS namespace portfolio, nine published websites, educational resources, and prototypes for managed subname delivery.

**[Explore the live portfolio](https://productpassport-eth.netlify.app/portfolio/)** · **[Architecture](docs/architecture.md)** · **[Verification and status](docs/verification.md)** · **[Professional profile](https://github.com/Reactance0083)**

## The problem

A product record, asset history, organization, or automated agent may need a stable way to be identified across systems. A name alone does not establish accuracy, authority, access rights, or ownership of the underlying asset.

This project explores where ENS can provide an optional naming and discovery layer, how to explain its limits, and what operational checks would be needed before offering managed naming services.

## My role

I own the portfolio and direct its product positioning, business requirements, workflow design, research priorities, and release decisions. Development and research use AI-assisted tools. I review user journeys and evidence, including failure states, ownership boundaries, and what is actually published.

## What is available

| Workstream | Implemented work | Status |
| --- | --- | --- |
| Public portfolio | Nine responsive sites, shared portfolio/inquiry routes, metadata, sitemaps, and educational crosslinks. | Published. |
| Education | Five research articles and four practical worksheets covering product records, identity, authority, and agent controls. | Published resources; later drafts are separate. |
| Managed-subname workflow | Checkout/account interfaces, order persistence, contract candidates, signature-bound delivery, receipt/recovery and lifecycle tests. | Prototype and gated implementation; public purchasing remains paused. |
| Release operations | Deployment manifests, checks for preserved files/functions, verification files, security headers, and scheduled functions. | Implemented operating process; release-specific evidence recorded privately. |

## Published sites

| Website | Focus |
| --- | --- |
| [Product Passport](https://productpassport-eth.netlify.app/) | Product identity and digital product passport discovery. |
| [DPP Registry](https://dppregistry-eth.netlify.app/) | Registry concepts and integration questions. |
| [Asset Records](https://assetrecords-eth.netlify.app/) | Authoritative records and cross-system references. |
| [Asset Passport](https://assetpassport-eth.netlify.app/) | Asset identity, provenance, and lifecycle evidence. |
| [Agent Permissions](https://agentpermissions-eth.netlify.app/) | Delegation, spending scope, expiry, and revocation. |
| [Intent Services](https://intentservices-eth.netlify.app/) | Agent intent, authorization, and machine commerce. |
| [Identity Mesh](https://identitymesh-eth.netlify.app/) | Agent identity and organizational credentials. |
| [Recognized Entities](https://recognizedentities-eth.netlify.app/) | Entity recognition and service discovery. |
| [Trust Fabric](https://trustfabric-eth.netlify.app/) | Digital trust and accountable transactions. |

Start with the [resource library](https://productpassport-eth.netlify.app/resources/), the [DPP registry explainer](https://dppregistry-eth.netlify.app/research/eu-dpp-registry-explained/), or the [asset-records article](https://assetrecords-eth.netlify.app/research/tokenized-assets-and-authoritative-records/).

## Technical scope

- HTML/CSS/JavaScript sites and Node.js services on Netlify.
- PostgreSQL-backed order and event records.
- Solidity contract candidates and ethers.js interactions.
- Local EVM simulations, signature/permission checks, replay protection, expiry, and restart recovery.
- Structured technical writing, responsive interfaces, release documentation, and scoped regression checks.

The published websites use conventional HTTPS hosting. Direct decentralized .eth website hosting is a separate capability. These are independent projects, with no claim of official ENS, government, or standards-body status.

## What the project demonstrates

Turning a broad blockchain concept into a concrete customer journey requires more than a landing page: naming rights, control, identity proof, payment evidence, delivery, renewals, recovery, and support all need explicit rules. This portfolio makes those dependencies visible and distinguishes a test result from a production launch.

**Current status, November 10, 2026:** public education continues; paid leasing rollout is on hold. Local tests and published pages do not establish an audited production registrar, successful customer sale, or customer adoption.

This repository contains a public project summary. The private working repository and its commercial records remain private.
