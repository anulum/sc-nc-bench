<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
SC-NC-BENCH — repository foundation
-->

# Architecture

## Current executable surface

The checkout contains:
- repository validation tooling;
- dedicated tests;
- workflow definitions;
- native documentation.

No domain component of SC-NC Bench is implemented yet, and no code has moved here from SC-NeuroCore. The metadata keeps domain capabilities, claims and qualified record formats empty.

## Intended records

1. **Workload suite:** A fixed set of workloads, with their inputs, metrics and acceptance rules.
2. **Adapter run:** One framework's run of a workload suite, with its environment and results.

## Ownership

**This project owns** the planned SC-NC Bench records and boundary rules.

**Owned elsewhere:**

| Responsibility | Owner |
|---|---|
| simulation | SC-NC Engine |
| energy models | SC-NC Compiler |
| cross-repository evidence | Neuro Evidence Bench |
| the public package, documentation and releases of the monolith | SC-NeuroCore |

## Interpretation

- **Benchmarks.** A result holds for its suite, environment and lane only.
- **Moves.** Code arrives only through SC-NeuroCore's split import gate, unit by unit; a planned move is not a moved capability.

Read [the documentation architecture](docs/ARCHITECTURE.md) for the planned records, rules and schema identifiers.
