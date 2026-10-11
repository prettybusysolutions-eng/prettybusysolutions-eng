# Pretty Busy Solutions

We build evidence-bound infrastructure for autonomous execution. **ProofRail is our flagship:** a tested protocol pilot for single-use authority, replay and drift denial, with explicit failure boundaries.

Start with the [ProofRail v0.6.0 pilot release](https://github.com/prettybusysolutions-eng/proofrail/releases/tag/v0.6.0): installable wheel, source distribution, checksums and exact-commit workflow metadata. Run the [10-minute break test](https://github.com/prettybusysolutions-eng/proofrail/blob/main/docs/QUICKSTART.md) and inspect the limitations before adoption.

## Pilot offer

We propose one bounded evaluation using synthetic data: install the tagged artifact, demonstrate one authorized action and its replay/drift failures, interrupt and restart the selected integration, then rehearse an upgrade. Agree on acceptance criteria and record the exact commit, results, latency and recovery behavior. Contact **prettybusysolutions@gmail.com** to scope a pilot or independent review. No engagement or customer result is implied by this offer.

## Evidence and maturity

ProofRail's source tests and installed-wheel reproduction run in author-controlled CI. **Independent semantic review and external reproduction remain pending.** A release, a signature and green CI do not establish independent assurance, production readiness or market adoption. ESRM source-conformance gates are separate from legacy ProofRail semantics.

| Repository | Current evidence | Maturity and remaining gate |
| --- | --- | --- |
| [ProofRail](https://github.com/prettybusysolutions-eng/proofrail) | Tagged pilot artifacts and repeatable break tests | Protocol pilot; independent review and operational key/checkpoint hardening pending |
| [VerifiAgent](https://github.com/prettybusysolutions-eng/verifiagent) | Truthful tri-state verdicts, authenticated durable jobs and constrained-worker configuration tests | Operator pilot; real isolated-worker and provider integration pending |
| [Adversarial Coder](https://github.com/prettybusysolutions-eng/adversarial-coder) | Known-bad target and missing-evidence tests | Framework alpha; adapters and external deployment validation pending |
| [IMOS](https://github.com/prettybusysolutions-eng/imos) | Owner-scoped SQLite decisions, restart and schema-boundary tests | Service pilot; graph/ingest and legacy migration unvalidated |
| [LeakLock](https://github.com/prettybusysolutions-eng/xzenia-leaklock) | Flask scanner, access/payment tests and PostgreSQL/Redis CI | Application pilot; real checkout, migration and deployed fulfillment pending |
| [DenialNet](https://github.com/prettybusysolutions-eng/denialnet) | Account-bound pattern access and atomic settlement tests with PostgreSQL/Redis CI | Application pilot; real provider flow, clinical validity and federation unproven |
| [Thermodynamic Substrate](https://github.com/prettybusysolutions-eng/thermodynamic-substrate) | Numerical, concurrent/restart invariants and reproducible SQLite overhead comparison | Research prototype; no demonstrated useful-work advantage |
| [Residue Classifier](https://github.com/prettybusysolutions-eng/residue-classifier) | Versioned filename-heuristic CLI and explicit report limits | Utility pilot; real-workspace accuracy unmeasured |
| [x402 MCP Server](https://github.com/prettybusysolutions-eng/x402-mcp-server) | Discovery and synthetic payment-boundary tests | Package prototype; real settlement/delivery/replay and synchronized distribution pending |

## Operating standard

Evidence before claims. Required behavior checks on the exact reviewed head. Missing evidence returns PARTIAL; demonstrated failure returns FAIL. Source access and Git cloning do not establish operational restoration. We publish measured limits alongside results.

[Open-source policy](OPEN_SOURCE_POLICY.md) · [Release policy](RELEASE_POLICY.md)
