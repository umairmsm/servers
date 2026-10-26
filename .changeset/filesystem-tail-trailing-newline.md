---
"@modelcontextprotocol/server-filesystem": patch
---

Fix `read_text_file` with `tail: N` returning N-1 lines when file ends with a newline (#5215).
