# aw-skills-r2-qa

Benign, static fixtures for QA of Atomicwork Skills Registry R2 (import from GitHub). Nothing here is malicious.

| Folder | Skill name | Purpose |
|---|---|---|
| `skills/qa-r2-gh-clean` | `qa-r2-gh-clean` | Clean single skill; edit upstream to test "changed upstream" |
| `skills/qa-r2-gh-multi` | `qa-r2-gh-multi` | Multi-file skill (references/, scripts/) |
| `skills/qa-r2-gh-tool` | `qa-r2-gh-tool` | `allowed-tools` names an MCP server that is not in the store |
| `skills/qa-r2-gh-big` | `qa-r2-gh-big` | About 5.7 MB across six reference files (over the 5 MB per-skill limit) |
| `skills/qa-r2-gh-dup-a`, `skills/qa-r2-gh-dup-b` | `qa-r2-gh-dup` (both) | Two folders sharing one frontmatter name (pack duplicate handling) |
| `skills/qa-r2-gh-auto-multi` | `qa-r2-gh-auto-multi` | Multi-file skill for UI automation (UI-IMP-001), deleted after each run |
| `skills/qa-r2-gh-pack-a`, `skills/qa-r2-gh-pack-b` | same as folder | Pack selection import for UI automation (UI-IMP-004) |
| `skills/qa-r2-gh-pick-a`, `skills/qa-r2-gh-pick-b` | same as folder | Pack picker selection, never imported (UI-IMP-003) |
| `skills/qa-r2-gh-cwk101-a`, `skills/qa-r2-gh-cwk101-b` | same as folder | Coworker pack import for UI automation (UI-CWK-101) |

Skill names carry no run suffix, so delete the imported skills after every test run.
