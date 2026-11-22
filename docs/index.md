<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
SC-NC-BENCH — repository foundation
-->

# SC-NC Bench

SC-NC Bench is being built as the benchmark layer split out of SC-NeuroCore: the workload suites that compare engines, compilers and trained networks, the adapter runs that put other frameworks on the same workloads, profiling, and the energy accounting that keeps measured and estimated figures apart. It imports SC-NC Core, SC-NC Engine, SC-NC Analysis, SC-NC Compiler, SC-NC Learn and SC-NC Bridges. Its current executable surface is repository validation tooling. It has no installed benchmark runner, workload suite, energy accountant or qualified record schema.

SC-NC Bench is part of the **SC Neuromorphic Computing Systems** group (SC-NEUROMORPHIC-COMPUTING-SYSTEMS). The [group and project map](https://github.com/anulum/sc-neurocore/blob/main/docs/ecosystem.md) shows the whole programme and where this repository sits in it.

Read [Architecture](ARCHITECTURE.md), [validation tooling](validation-tooling.md), [data boundaries](THREAT_MODEL.md) and the [repository boundary decision](adr/0001-repository-boundary.md).
