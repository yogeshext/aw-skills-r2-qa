# aw-skills-r2-qa

Benign, static fixtures for QA of Atomicwork Skills Registry R2 (import from GitHub). Nothing here is malicious.

| Folder | Skill name | Purpose |
|---|---|---|
| `skills/qa-r2-gh-clean` | `qa-r2-gh-clean` | Clean single skill; edit upstream to test "changed upstream" |
| `skills/qa-r2-gh-multi` | `qa-r2-gh-multi` | Multi-file skill (references/, scripts/) |
| `skills/qa-r2-gh-tool` | `qa-r2-gh-tool` | `allowed-tools` names an MCP server that is not in the store |
| `skills/qa-r2-gh-big` | `qa-r2-gh-big` | About 5.7 MB across six reference files (over the 5 MB per-skill limit) |
| `skills/qa-r2-gh-dup-a`, `skills/qa-r2-gh-dup-b` | `qa-r2-gh-dup` (both) | Two folders sharing one frontmatter name (pack duplicate handling) |

Skill names carry no run suffix, so delete the imported skills after every test run.
