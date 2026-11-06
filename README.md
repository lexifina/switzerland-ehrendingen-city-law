# Ehrendingen (city): law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Ehrendingen, Aargau, Switzerland, which global-law reads at `switzerland/aargau/ehrendingen/acts/`.

The municipal law of the municipality of Ehrendingen (Gemeinde Ehrendingen, canton of Aargau, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law). The law of the canton of Aargau is in [lexifina/switzerland-aargau-law](https://github.com/lexifina/switzerland-aargau-law); federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, exactly as the municipality publishes it.

## What this repository holds

38 acts with 44 versions so far: the Gemeindeordnung (the municipality's charter) first, then the municipality's other enactments in force (ordinances, regulations, tariffs and decisions), in the order of the systematic collection, added in parts of about 50. Agreements, concessions, directives and repealed acts are not included.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `1-1-1/` | Gemeindeordnung (SRS 1.1-1) | 2 | oldest version available, then each consolidated version: 1 January 2022 to 1 January 2026 |
| `1-3-1-informations-datenschutz-archiv-und-gebuhrenreglement/` | Reglement über die Information der Öffentlichkeit, den Datenschutz, das Archivwesen und die Gebühren (RIDAG) (SRS 1.3-1) | 1 | one version (the oldest available), 9 May 2016 |
| `1-3-2/` | Kommunikationskonzept (SRS 1.3-2) | 1 | as enacted, 22 August 2016 |
| `1-6-1-gkr/` | Geschäfts- und Kompetenzreglement (SRS 1.6-1) | 2 | oldest version available, then each consolidated version: 1 August 2017 to 1 January 2026 |
| `1-6-2-grgl/` | Geschäftsreglement der Geschäftsleitung (SRS 1.6-2) | 1 | one version (the oldest available), 1 August 2021 |
| `1-6-3-entschadigungsreglement/` | Reglement über die Entschädigungen der Behörden, Kommissionen und Funktionäre (SRS 1.6-3) | 2 | oldest version available, then each consolidated version: 30 October 2023 to 1 January 2026 |
| `1-7-1/` | Personalhandbuch (SRS 1.7-1) | 1 | as enacted, 1 January 2019 |
| `1-7-1-1/` | Ausführungsbestimmungen zum Personalhandbuch (SRS 1.7-1.1) | 1 | one version (the oldest available), 13 May 2024 |
| `1-7-1-2-betriebliche-grundbildung/` | Konzept für die Ausbildung von Lernenden und Praktikanten der Gemeinde Ehrendingen nach Bildungsverordnung 2023 (SRS 1.7-1.2) | 1 | one version (the oldest available), 1 May 2019 |
| `1-7-1-3/` | Entschädigungsansätze Amtsperiode 2026/2029 (SRS 1.7-1.3) | 2 | as enacted, then each consolidated version: 1 January 2022 to 1 January 2026 |
| `1-8-1-ortsburgerreglement/` | Reglement über den Erwerb des Ortsbürgerrechts der Gemeinde Ehrendingen (SRS 1.8-1) | 1 | as enacted, 1 January 2021 |
| `1-8-2/` | Übertragung der Befugnis an den Gemeinderat zum Erwerb, zur Veräusserung und zum Tausch von Grundstücken und Liegenschaften der Ortsbürgergemeinde sowie die Einräumung von Rechten an solchen bis zum Betrage von CHF 100'000.00 pro Amtsperiode (SRS 1.8-2) | 1 | as enacted, 9 July 2008 |
| `1-8-3/` | Reglement über die Errichtung eines Waldfonds (SRS 1.8-3) | 1 | as enacted, 1 January 2019 |
| `4-1-1-elternbeitragsreglement/` | Reglement über die Beteiligung der Gemeinde Ehrendingen an den Elternbeiträgen bei Tagesstrukturen Ehrendingen, Verein Chinderhuus Surbtal, übrigen Kindertagesstätten, Tagesfamilien, Musikschule Ehrendingen sowie Dyskalkulietherapie (SRS 4.1-1) | 1 | as enacted, 1 March 2019 |
| `4-1-2/` | Qualitätsstandards für Kindertagesstätten, Tagesstrukturen und Tagesfamilien (SRS 4.1-2) | 1 | as enacted, 1 January 2019 |
| `4-1-3/` | Betriebskonzept und ‑reglement der Tagesstrukturen (SRS 4.1-3) | 1 | as enacted, 1 January 2019 |
| `4-1-4/` | Ernährungskonzept Tagesstrukturen (SRS 4.1-4) | 1 | as enacted, 1 January 2020 |
| `4-1-5/` | Pädagogisches Konzept Tagesstrukturen (SRS 4.1-5) | 1 | as enacted, 1 January 2020 |
| `4-1-6/` | Verhaltenskodex in Bezug auf sexuelle Gewalt für die Mitarbeitenden der Tagesstrukturen (SRS 4.1-6) | 1 | as enacted, 1 January 2019 |
| `4-1-7/` | Sicherheitskonzept Tagesstrukturen (SRS 4.1-7) | 1 | as enacted, 1 January 2020 |
| `4-3-1/` | Allgemeines Reglement Musikschule (SRS 4.3-1) | 1 | one version (the oldest available), 1 January 2023 |
| `4-3-2/` | Reglement über das Anstellungsverhältnis der Musiklehrpersonen und des Musikschulleiters (SRS 4.3-2) | 1 | as enacted, 1 March 2007 |
| `4-8-1-beitragsreglement-vereine/` | Konzept über die Beiträge der Gemeinde Ehrendingen an die Vereine (SRS 4.8-1) | 1 | one version (the oldest available), 1 January 2024 |
| `5-1-1/` | Polizeireglement der Gemeinden Baden, Birmenstorf, Ehrendingen, Ennetbaden, Freienwil, Gebenstorf, Obersiggenthal, Untersiggenthal und Würenlingen (SRS 5.1-1) | 2 | as enacted, then each consolidated version: 1 January 2016 to 1 July 2025 |
| `5-5-1/` | Feuerwehrreglement Feuerwehr Ehrendingen-Freienwil (SRS 5.5-1) | 1 | as enacted, 4 February 2008 |
| `5-5-1-1-einsatzkostentarif/` | Tarif über die Entschädigung von Einsatzkosten im Feuerwehrwesen (SRS 5.5-1.1) | 2 | as enacted, then each consolidated version: 1 August 1997 to 1 January 2026 |
| `6-6-1/` | Verwaltungsreglement Schiessanlage Sackhölzli Ober-Ehrendingen (SRS 6.6-1) | 1 | as enacted, 26 May 1997 |
| `6-6-2/` | Reglement über die Benutzung von Räumen und Sportplätzen der Gemeinde Ehrendingen (SRS 6.6-2) | 1 | one version (the oldest available), 1 January 2020 |
| `7-1-1/` | Bau- und Nutzungsordnung (SRS 7.1-1) | 1 | one version (the oldest available), 22 November 2010 |
| `7-1-2/` | Gebührenreglement zur Bau- und Nutzungsordnung (BNO) (SRS 7.1-2) | 1 | as enacted, 1 January 2022 |
| `7-4-3-1/` | Abwasserreglement (SRS 7.4.3-1) | 1 | as enacted, 26 July 2006 |
| `7-4-4-1/` | Abfallreglement (SRS 7.4.4-1) | 1 | one version (the oldest available), 1 January 2013 |
| `7-6-1-rfsa/` | Reglement für die Finanzierung von Strassen und Anlagen der Abwasserbeseitigung (SRS 7.6-1) | 1 | one version (the oldest available), 1 January 2017 |
| `7-6-2/` | Reglement für die Erhebung von Strassenbaubeiträgen (SRS 7.6-2) | 1 | as enacted, 12 July 1999 |
| `7-6-3/` | Winterdienstkonzept (SRS 7.6-3) | 1 | as enacted, 10 November 2008 |
| `7-7-1/` | Parkraumkonzept (SRS 7.7-1) | 1 | as enacted, 30 September 2020 |
| `8-2-1/` | Bestattungs- und Friedhofreglement (SRS 8.2-1) | 1 | one version (the oldest available), 1 January 2025 |
| `9-2-1/` | Reglement über die Sicherung und den Unterhalt der landwirtschaftlichen Infrastrukturanlagen im Gemeindegebiet Ehrendingen (SRS 9.2-1) | 1 | as enacted, 21 July 2010 |

## Source

The SRS (systematic collection) of the municipality, published by the municipality at <https://ehrendingen.tlex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

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

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@ehrendingen.tlex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the municipality publishes as binding. The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
