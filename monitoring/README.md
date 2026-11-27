<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Beobachtung: was gelesen wird und was daraus folgte

[English](README.en.md)

Wie global-law jedes Land beobachtet: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). Diese Seite zeigt dasselbe nur für Nidwalden: jedes Lesen einer amtlichen Quelle, wann, und was daraus folgte (Vorschriften hinzugefügt, geändert und entfernt). Maschinenlesbar in [data/checks/](../data/checks/) (JSON Lines, Schema `lexifina-check/1`), in `git log` als Commits mit `Kind: check` und Monat für Monat in [checks/](checks/).

**Letzte Prüfung:** 2026-11-27 06:36 UTC, Nidwalden: Systematische Sammlung (gesetze.nw.ch): 169 Adressen gelesen; 0 hinzugefügt, 0 geändert, 0 entfernt; keine Änderung; 3 nicht veröffentlicht, davon 0 ohne Grund. Hinweise: `verify-differ`.

## Quellen

| Quelle | Ordner | Wie oft | Letzte erfolgreiche Prüfung | Letztes Ergebnis | Stand |
| --- | --- | --- | --- | --- | --- |
| [Nidwalden: Systematische Sammlung (gesetze.nw.ch)](https://gesetze.nw.ch/) | `<act>/` | täglich | 2026-11-27 06:36 UTC | keine Änderung | beobachtet |

## Die letzten 30 Tage

| Beginn (UTC) | Quelle | Gelesen | Hinzugefügt | Geändert | Entfernt | Nicht veröffentlicht (ohne Grund) | Ergebnis | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-27 06:33](checks/2026-11.md#ch-lexwork-nidwalden-20261127t063344z) | lexwork-nidwalden | 169 | 0 | 0 | 0 | 3 (0) | keine Änderung `verify-differ` | — |
| [2026-11-26 06:33](checks/2026-11.md#ch-lexwork-nidwalden-20261126t063336z) | lexwork-nidwalden | 74 | 0 | 0 | 0 | 2 (0) | keine Änderung `verify-differ` | — |
| [2026-11-25 07:15](checks/2026-11.md#ch-lexwork-nidwalden-20261125t071554z) | lexwork-nidwalden | 240 | 132 | 0 | 0 | 1 (0) | Änderungen gefunden `verify-differ` | [208](https://github.com/lexifina/switzerland-nidwalden-law/compare/d6d314f4459f...23329a6cdfbe) |
| [2026-11-24 14:57](checks/2026-11.md#ch-lexwork-nidwalden-20261124t145748z) | lexwork-nidwalden | 173 | 132 | 0 | 0 | 134 (0) | die Prüfung ist fehlgeschlagen | — |
| [2026-11-24 12:12](checks/2026-11.md#ch-lexwork-nidwalden-20261124t121218z) | lexwork-nidwalden | 392 | 133 | 0 | 0 | 134 (0) | die Prüfung ist fehlgeschlagen | — |

## Selbst prüfen

```
python tools/checktrail.py                      # die letzte Prüfung jeder Quelle
python tools/checktrail.py --day 2026-11-23     # jede Prüfung eines Tages
python tools/checktrail.py --act <id>           # wann eine Vorschrift gesehen und veröffentlicht wurde
git log --grep='^Kind: check' --format='%ci %s'  # die Prüfungen in der Historie
```

Rechtskraft hat nur die amtliche Verkündung; die Texte hier sind Kopien zum Lesen und Suchen.
