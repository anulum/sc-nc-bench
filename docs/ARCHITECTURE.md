<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
SC-NC-BENCH — repository foundation
-->

# Repository architecture

## Current executable tooling

**What it contains:** the repository's metadata, source-provenance, workflow, dependency-alignment, documentation, inventory and preflight controls.

**What each control does:** it inspects its fixed, declared local scope.

**What received metadata cannot do:** select another acceptance policy or grant domain authority.

Foundation qualification is in progress.

## Intended domain boundaries

| Record | Responsibility | Required evidence |
| --- | --- | --- |
| Workload suite | A fixed set of workloads, with their inputs, metrics and acceptance rules | Workloads and metrics fixed before any run |
| Adapter run | One framework's run of a workload suite, with its environment and results | Environment recorded and results compared only within the same suite |

## Planned record schemas

- `sc_nc_bench.workload_suite.v1`
- `sc_nc_bench.adapter_run.v1`

These are planned identifiers. None of them is registered or qualified here.

It also takes over, unchanged, the MLPerf-style result schema of SC-NeuroCore from SC-NeuroCore when their code moves here.

Read [validation tooling](validation-tooling.md) for the executable repository interfaces.
