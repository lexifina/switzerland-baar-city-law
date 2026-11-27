<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Baar only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-27 07:06 UTC, Baar: systematic collection (baar.tlex.ch): 15 addresses read; 0 added, 0 changed, 0 removed; no change; 60 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Baar: systematic collection (baar.tlex.ch)](https://baar.tlex.ch/) | `<act>/` | daily | 2026-11-27 07:06 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-27 07:05](checks/2026-11.md#ch-lexwork-baar-city-20261127t070548z) | lexwork-baar-city | 15 | 0 | 0 | 0 | 60 (0) | no change | — |
| [2026-11-26 07:11](checks/2026-11.md#ch-lexwork-baar-city-20261126t071135z) | lexwork-baar-city | 15 | 0 | 0 | 0 | 60 (0) | no change | — |
| [2026-11-25 08:19](checks/2026-11.md#ch-lexwork-baar-city-20261125t081937z) | lexwork-baar-city | 18 | 0 | 0 | 0 | 60 (0) | no change | — |
| [2026-11-24 12:42](checks/2026-11.md#ch-lexwork-baar-city-20261124t124255z) | lexwork-baar-city | 74 | 60 | 0 | 0 | 60 (0) | changes found | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
