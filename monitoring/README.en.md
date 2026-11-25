<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Nidwalden only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-25 07:23 UTC, Nidwalden: systematic collection (gesetze.nw.ch): 240 addresses read; 132 added, 0 changed, 0 removed; changes found; 1 not published, 0 of them with no reason. Flags: `verify-differ`.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Nidwalden: systematic collection (gesetze.nw.ch)](https://gesetze.nw.ch/) | `<act>/` | daily | 2026-11-25 07:23 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-25 07:15](checks/2026-11.md#ch-lexwork-nidwalden-20261125t071554z) | lexwork-nidwalden | 240 | 132 | 0 | 0 | 1 (0) | changes found `verify-differ` | [208](https://github.com/lexifina/switzerland-nidwalden-law/compare/d6d314f4459f...23329a6cdfbe) |
| [2026-11-24 14:57](checks/2026-11.md#ch-lexwork-nidwalden-20261124t145748z) | lexwork-nidwalden | 173 | 132 | 0 | 0 | 134 (0) | the check failed | — |
| [2026-11-24 12:12](checks/2026-11.md#ch-lexwork-nidwalden-20261124t121218z) | lexwork-nidwalden | 392 | 133 | 0 | 0 | 134 (0) | the check failed | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
