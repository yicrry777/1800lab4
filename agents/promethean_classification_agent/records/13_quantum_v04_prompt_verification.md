# Version 0.4 prompt verification — 2026-10-18

The unchanged `tools/build_prompt.py` generated the primary, university contrast and hype-bank contrast prompt packets saved as `quantum_v04_*_prompt.txt`. Lengths are 11,723, 11,724 and 11,813 characters respectively. Each packet contains `agent.version` 0.4 and the citation identity gate. `python3 tools/check_frozen_core.py` returned `FROZEN CORE INTACT`.

This check verifies that the revised instruction reached each ChatGPT input and that the frozen scaffold remains intact. Whether the rule improves output citation accuracy requires a separate independent ChatGPT retest and original-source check.
