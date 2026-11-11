# Verification scope and current status

[Back to project](../README.md)

## Evidence categories

| Category | Evidence represented | What it establishes |
| --- | --- | --- |
| Published website | Public pages and educational resources, with dated release records. | The described content is available on the web. |
| Local integration | Simulated payments, local-chain transactions, persisted orders, and restart tests. | Specified behavior under the tested conditions. |
| Read-only chain checks | Recorded registry/ownership and coverage observations. | Observed on-chain state at a particular time. |
| Customer acceptance | A real hosted order, payment, correct delivery, receipt, and lifecycle review. | Still a separate release requirement. |

## Failure cases covered by the prototype work

- Payment amount, currency, recipient, or order does not match.
- A signature is invalid, expired, or bound to the wrong domain or terms.
- A payment or fulfillment authorization is replayed.
- A name is reserved, already active, or outside delegated scope.
- A process restarts after payment or loses a transaction response.
- The parent registration does not cover the proposed annual lease.
- Root management is revoked or a lease expires.
- A later registration could otherwise expose a prior customer's records.

These describe historical implementation and test coverage in the working project. This documentation refresh does not claim a new full test run or an independent security audit.

## Current release position

As of November 10, 2026:

- Nine portfolio websites and the published educational resources are public.
- Managed naming and commerce components exist in source and test environments.
- Paid leasing setup and rollout remain paused.
- Customer adoption, revenue, external editorial acceptance, and independent contract review are not inferred from publication or testing.
- Private visual lessons and later resource drafts are not presented here as published products.

## Release discipline

A site update must preserve the existing files and backend components outside its intended scope. The project records file/function digests, route checks, security configuration, and publication outcomes. A missing exact deployment dependency can stop a release while leaving the current site available.

That operating distinction is part of the project: prepared source, successful tests, deployed code, and accepted customer behavior are different milestones.
