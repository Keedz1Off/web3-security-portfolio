# Results, candidates and learning examples

Reviewed for this portfolio index on **31 October 2026**. These classifications describe inspected public sources and retained historical evidence; this publication update does not rerun the targets or verify current chain deployments.

## Publicly acknowledged, fixed finding: Voxel Bench SR-01

[Dedicated case study](https://github.com/Keedz1Off/voxel-bench-sr01-case-study) · [Project acknowledgement](https://github.com/ETH-GLOBAL-ONLINE/voxel-bench/blob/2734fc4e31a6763986a62d5bdf2704e770c1c71d/docs/CONTRACT_AUDIT.md#findings)

An observer of an unclaimed recipe ID could register themselves as author through an unrestricted publication path and receive future author royalties. The signed path proved control of the claimant's wallet, not provenance of the recipe.

The project credits Stefan for SR-01, identifies AI assistance, documents the fix, and retains the historical direct-path PoC output plus fixed regression results. The implemented fix restricts both publication routes to an attester and checks claim eligibility in the agent. The attester remains a trusted component.

Source snapshots and evidence are linked in the dedicated case. The project is an ETHOnline 2026 hackathon application. No CVE, bounty payment, prize, real-user loss or current-mainnet exposure is claimed.

## Other Web3 work

| Material | Supported public statement | Evidence limit |
| --- | --- | --- |
| [Katana test extract](https://github.com/Keedz1Off/katana-vault-bridge-invariant-fuzzing) | Five stateful flows, nineteen invariant functions, eleven stateless fuzz tests; historical suite results of 24 + 11 passes. | Explicit local mocks; no public vulnerability proof in that extract. |
| [Push Chain review](https://github.com/Keedz1Off/push-chain-gateway-flow-local-review) | 27 checks: 23 protected and four suspicious checks grouped into one event-data-integrity candidate; zero confirmed vulnerabilities recorded. | The candidate still requires an end-to-end trace or PoC. |
| [Arbitrum](https://github.com/Keedz1Off/arbitrum-bridge-flow-local-review), [Optimism](https://github.com/Keedz1Off/optimism-bridge-flow-local-review), [LayerZero](https://github.com/Keedz1Off/layerzero-oft-flow-local-review) | Architecture reviews, function notes, invariant practice and simplified labs. | Deliberately broken examples are not findings against the upstream protocols. |
| [Sky](https://github.com/Keedz1Off/Keedz1Off-sky-dai-fork-local-review), [Arbitrum L3](https://github.com/Keedz1Off/arbitrum-l3-bridge-flow-local-review) | Supporting architecture studies. | No completed production-audit or confirmed-finding claim. |

An unresolved candidate stays a candidate. A local test result stays scoped to its actual setup. A closed finding keeps its original vulnerable snapshot distinct from fixed source.

Read [FLOW.md](FLOW.md) for the method and [READING-GUIDE.md](READING-GUIDE.md) for navigation.
