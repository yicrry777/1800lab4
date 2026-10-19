# Revised prompt construction check

Date: 2026-10-18. Agent version 0.2. Rebuilt all three packets with the unchanged `tools/build_prompt.py`; every command exited 0. The generated files stay in ignored `work/`; regenerate them from the committed agent and cases.

| Case | SHA-256 of generated packet |
| --- | --- |
| primary | `a7503d3746f8dca3028c55f65bee65c45fbf60736245c08e2d75122f424ea45d` |
| contrast_1 | `6448990e8709122d357e08029235c2cbe94aac68276f5a300b28bac369ca1b4f` |
| contrast_2 | `d32995711034860248fb93d5770ee13d3b1604b868a67366110f83e971eb35a9` |

For the worked example response runs, Codex used these packets with the verified source dossier in `sources.md`. A future ChatGPT operator should supply or independently check those original sources; if current evidence cannot be checked, the agent's abstention rule applies. The local validator checks response structure, so the test record also reviews whether conclusions match the sources.
