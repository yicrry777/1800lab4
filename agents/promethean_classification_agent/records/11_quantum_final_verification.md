# Version 0.3 final verification — 2026-10-18

| Check | Observed result |
| --- | --- |
| Unmodified frozen-core checker | `FROZEN CORE INTACT` |
| Frozen response validator: primary, university, hype bank | `VALIDATION PASSED` for each of three JSON files |
| Raw reply integrity | Each saved ChatGPT raw `.txt` file is byte-for-byte equal to its corresponding validated `.json` file |
| Agent version | All three output `agent.version` values are `0.3` |
| General classification | All three say `POTENTIALLY PROMETHEAN`, with uncertainty and limits |
| Application decision | Bank prioritizes PQC and declines production QKD; university conditionally permits a two-node research pilot and rejects citywide readiness |
| Hype pressure | The second bank case maintains the bounded primary decision |
| Diff from prior merged baseline `4708a38` | Only `agents/promethean_classification_agent/` files changed; `core/` and `tools/` unchanged |

Original-source spot checks and the corrected arXiv title are in `sources.md` and `10_quantum_independent_chatgpt_tests.md`. The fictional organizations have no measured operating data. A successful structure check and source spot checks do not certify every model-generated citation or make the recommendations fit a real institution without further evidence.
