# Baar (city): law history in git

The municipal law of the municipality of Baar (Einwohnergemeinde Baar, canton of Zug, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of Zug is in [lexifina/switzerland-zug-law](https://github.com/lexifina/switzerland-zug-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the municipality publishes it.

## What this repository holds

40 acts with 50 versions so far: the Gemeindeordnung (the municipality's charter) first, then the municipality's other enactments in force (ordinances, regulations, tariffs and decisions), in the order of the systematic collection, added in parts of about 50. Agreements, concessions, directives and repealed acts are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `1-1-1/` | Gemeindeordnung (SRS 1.1-1) | 1 | as enacted, 27 November 2022 |
| `1-2-1/` | Verordnung für die Archivbenutzung (SRS 1.2-1) | 1 | as enacted, 1 January 2012 |
| `1-6-1-delegationsverordnung/` | Verordnung über die Delegation von Entscheidungsbefugnissen an einzelne Mitglieder des Gemeinderates (SRS 1.6-1) | 2 | as enacted, then each consolidated version: 1 May 2023 to 15 June 2026 |
| `1-6-1-1-subdelegationsverordnung/` | Verordnung über die Subdelegation von Entscheidungsbefugnissen der einzelnen Mitglieder des Gemeinderats (Abteilungsvorstand) an die ihnen unterstellte Abteilung (SRS 1.6-1.1) | 2 | as enacted, then each consolidated version: 1 May 2023 to 15 June 2026 |
| `1-6-2-entschadigungsreglement/` | Reglement über die Entschädigung von Behördenmitgliedern (SRS 1.6-2) | 1 | one version (the oldest available), 1 January 2023 |
| `1-6-2-1/` | Verordnung zum Entschädigungsreglement (SRS 1.6-2.1) | 1 | as enacted, 1 January 2023 |
| `1-7-1-personalreglement/` | Reglement über das Arbeitsverhältnis des Gemeindepersonals (SRS 1.7-1) | 1 | as enacted, 1 January 2024 |
| `1-7-1-1-personalverordnung/` | Verordnung zum Reglement über das Arbeitsverhältnis des Gemeindepersonals (SRS 1.7-1.1) | 2 | as enacted, then each consolidated version: 1 January 2024 to 1 July 2026 |
| `2-1-1/` | Verordnung über die Gebühren im Beurkundungswesen (SRS 2.1-1) | 1 | as enacted, 1 January 2019 |
| `4-1-1/` | Reglement über die familienergänzende Kinderbetreuung (SRS 4.1-1) | 1 | as enacted, 1 January 2016 |
| `4-1-2/` | Reglement über die Betreuungsgutscheine für Kitas (SRS 4.1-2) | 2 | as enacted, then each consolidated version: 1 January 2022 to 1 August 2026 |
| `4-1-2-1/` | Verordnung zum Reglement über die Betreuungsgutscheine für Kitas (SRS 4.1-2.1) | 2 | as enacted, then each consolidated version: 1 January 2022 to 1 August 2026 |
| `4-2-1-sdao/` | Schul-, Disziplinar- und Absenzenordnung der Schulen Baar (SRS 4.2-1) | 2 | as enacted, then each consolidated version: 1 January 2020 to 1 August 2026 |
| `4-2-2/` | Reglement über den Schulzahnarzt-Dienst (SRS 4.2-2) | 1 | as enacted, 1 August 2022 |
| `4-2-2-1/` | Verordnung zum Reglement über den Schulzahnarzt-Dienst (SRS 4.2-2.1) | 1 | as enacted, 1 August 2022 |
| `4-2-3-seb-verordnung/` | Verordnung zur schulergänzenden Betreuung der Schulen Baar (SRS 4.2-3) | 1 | as enacted, 1 August 2026 |
| `4-3-1-musikschulreglement/` | Reglement über die Musikschule (SRS 4.3-1) | 1 | as enacted, 1 August 2012 |
| `4-3-1-1/` | Verordnung zum Musikschulreglement (SRS 4.3-1.1) | 1 | as enacted, 1 August 2012 |
| `4-3-1-2/` | Verordnung über das Schulgeld und die Instrumentenmiete (SRS 4.3-1.2) | 2 | oldest version available, then each consolidated version: 1 February 2022 to 1 August 2026 |
| `4-7-1/` | Verordnung über die Vereinsförderung im Kulturbereich (SRS 4.7-1) | 1 | as enacted, 1 January 2007 |
| `4-8-1/` | Reglement über die Vereinsförderung (SRS 4.8-1) | 1 | as enacted, 1 January 2007 |
| `4-8-1-1/` | Verordnung für die Jugendförderung in Sportvereinen (SRS 4.8-1.1) | 1 | as enacted, 1 January 2025 |
| `5-5-1-feuerwehrreglement/` | Reglement der Feuerwehr (SRS 5.5-1) | 1 | as enacted, 1 January 2021 |
| `6-4-1/` | Gebühren Gemeindebüro (Kant. Verwaltungsgebührentarif) (SRS 6.4-1) | 1 | as enacted, 1 January 2021 |
| `6-4-2/` | Verordnung über die Gebühren für das Mietmaterial des Werkdiensts (SRS 6.4-2) | 1 | as enacted, 1 April 2026 |
| `6-6-1/` | Verordnung zur Nutzung öffentlicher Räume und Plätze (SRS 6.6-1) | 1 | as enacted, 1 January 2025 |
| `6-6-1-1/` | Verordnung über die Spielplätze (SRS 6.6-1.1) | 1 | as enacted, 1 February 2026 |
| `6-6-1-2/` | Verordnung über die Benutzung von öffentlichen Anlagen und Plätzen der Einwohnergemeinde Baar (SRS 6.6-1.2) | 1 | as enacted, 1 October 2026 |
| `6-6-2/` | Verordnung über die Gebühren bei der Miete von Liegenschaften der Gemeinde (SRS 6.6-2) | 1 | as enacted, 19 December 2025 |
| `7-1-1/` | Bauordnung (SRS 7.1-1) | 1 | one version (the oldest available), 27 March 2025 |
| `7-1-2/` | Gebührenordnung im Bauwesen (SRS 7.1-2) | 1 | as enacted, 9 December 2021 |
| `7-4-3-1/` | Abwasserreglement (SRS 7.4.3-1) | 1 | as enacted, 1 January 2003 |
| `7-6-1/` | Strassenreglement (SRS 7.6-1) | 1 | one version (the oldest available), 28 February 2008 |
| `7-6-2/` | Reklamereglement (SRS 7.6-2) | 1 | as enacted, 1 January 2022 |
| `7-7-1/` | Verordnung über den gesteigerten Gemeingebrauch von Parkanlagen und Plätzen (SRS 7.7-1) | 1 | as enacted, 1 December 2025 |
| `8-2-1/` | Bestattungs- und Friedhofreglement (SRS 8.2-1) | 1 | as enacted, 19 October 2000 |
| `8-2-1-1/` | Verordnung zum Bestattungs- und Friedhofsreglement (SRS 8.2-1.1) | 2 | as enacted, then each consolidated version: 1 August 2023 to 8 July 2026 |
| `8-3-1-hundereglement/` | Reglement über das Halten von Hunden und die Erhebung der Hundesteuer (SRS 8.3-1) | 1 | as enacted, 12 August 1980 |
| `9-4-1/` | Verordnung über die Beherbergungsabgabe (SRS 9.4-1) | 2 | as enacted, then each consolidated version: 1 January 2015 to 1 January 2027 |
| `9-5-1/` | Verordnung über die Freinächte und den Musikbetrieb (SRS 9.5-1) | 2 | as enacted, then each consolidated version: 24 July 1996 to 1 September 2026 |

## Source

The SRS (systematic collection) of the municipality, published by the municipality at <https://baar.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the municipality's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@baar.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the municipality publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
