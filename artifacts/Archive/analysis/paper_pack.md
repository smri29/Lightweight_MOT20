# MOT20 — Online vs Relinked (Train)

| Seq      | Variant   |   IDF1 |   MOTA |   MOTP |   IDSW | src    |
|:---------|:----------|-------:|-------:|-------:|-------:|:-------|
| MOT20-01 | Online    | 65.525 | 44.706 | 80.701 |    154 | online |
| MOT20-01 | Relink    | 55.781 | 29.451 | 71.222 |    123 | relink |
| MOT20-02 | Online    | 62.306 | 41.223 | 81.716 |   1317 | online |
| MOT20-02 | Relink    | 53.432 | 27.918 | 71.597 |    801 | relink |
| MOT20-03 | Online    | 65.388 | 45.804 | 80.806 |   1263 | online |
| MOT20-03 | Relink    | 57.231 | 33.369 | 69.437 |    502 | relink |
| MOT20-05 | Online    | 65.088 | 44.218 | 80.699 |   4031 | online |
| MOT20-05 | Relink    | 56.92  | 31.666 | 72.186 |   1758 | relink |

## Macro (mean / sum IDSW)

| Variant   |   IDF1 |   MOTA |   MOTP |   IDSW |
|:----------|-------:|-------:|-------:|-------:|
| Online    | 64.577 | 43.988 |  80.98 |   6765 |
| Relink    | 55.841 | 30.601 |  71.11 |   3184 |

**Decision:** Use ONLINE for test; relink hurt IDF1/MOTA.
