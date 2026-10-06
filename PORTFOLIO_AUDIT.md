# Portfolio Audit

| Repository | Problem | Severity | Proposed change | Reason | Verification method |
|---|---|---|---|---|---|
| Mingoomato | Profile links to repositories that are not publicly reachable | P1 | Remove inaccessible links and keep only verified public projects | Prevents recruiters from landing on dead or unavailable projects | Check each README URL and `git ls-remote` before/after |
| Mingoomato | README makes unsupported portfolio-wide license claim | P0 | Remove the blanket claim | The referenced repositories do not share one license | Inspect README and repository license files |
| Mingoomato | Opening profile emphasizes quantitative finance over current AI/backend work | P2 | Reorder and rewrite the short profile intro and project list | Aligns the profile with the actual engineering portfolio without adding claims | Review README links, wording, and diff |
