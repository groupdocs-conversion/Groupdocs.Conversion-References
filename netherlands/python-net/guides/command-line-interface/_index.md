---
title: "Commandoregelinterface"
linkTitle: "Command Line Interface"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Converteer documenten rechtstreeks vanuit de terminal met de groupdocs-conversion commandoregeltool — geen Python‑script vereist. Inspecteer documenten, lijst ondersteunde formaten op en pas een licentie toe, allemaal vanuit de shell."
type: docs
url: /nl/python-net/guides/command-line-interface/
is_root: false
weight: 120
---


Het installeren van het `groupdocs-conversion-net`‑pakket plaatst ook een `groupdocs-conversion` console‑script in je `PATH`. Het is een dunne wrapper rond de Python‑API, gebouwd voor gevallen waarin het opzetten van een Python‑script overbodig is — shell‑pijplijnen, Make‑regels, CI‑stappen en eenmalige conversies.

## Prerequisites

De CLI wordt meegeleverd in het pakket, dus extra installatie is niet nodig. Zorg ervoor dat `groupdocs-conversion-net` is geïnstalleerd (zie de [Quick Start Guide]()), controleer vervolgens of het console‑script beschikbaar is:

```bash
groupdocs-conversion --version
```

Je zou de pakketversie moeten zien afgedrukt, bijvoorbeeld `groupdocs-conversion 26.9.0`.

Als het `groupdocs-conversion`‑commando niet wordt gevonden, staat de scriptmap van het pakket mogelijk niet in je `PATH`. Je kunt de CLI altijd via de Python‑module‑vorm aanroepen: `python -m groupdocs.conversion`. Beide zijn equivalent.

## Commands

De CLI biedt vier subcommando's. Voer `groupdocs-conversion --help` uit voor de volledige lijst met vlaggen, of `groupdocs-conversion <command> --help` voor een specifiek subcommando.

### convert

Converteer een document naar een ander formaat. Het doelformaat wordt afgeleid van de extensie van het uitvoerbestand; geef `--format` op om dit te overschrijven.

```bash
# Extensie bepaalt het doelformaat
groupdocs-conversion convert business-plan.docx business-plan.pdf

# Overschrijf het formaat wanneer de uitvoernaam geen bruikbare extensie bevat
groupdocs-conversion convert business-plan.docx output.bin --format pdf

# Converteer een enkele pagina (1‑geïndexeerd) — handig voor rasterdoelen
groupdocs-conversion convert annual-review.pdf page1.png --page 1 --count 1

# Open een wachtwoord‑beveiligde bron
groupdocs-conversion convert protected.docx protected.pdf --password "secret"
```

| Optie | Beschrijving |
| :- | :- |
| `--format` | Doelformaat‑token (overschrijft de uitvoer‑extensie). |
| `--password` | Wachtwoord voor een beveiligd brondocument. |
| `--page` | Eerste pagina om te converteren, 1-geïndexeerd. |
| `--count` | Aantal pagina's om te converteren. |

Bij succes drukt het commando het uitvoerpad af en sluit af met code `0`.

### info

Print basisinformatie over een document — formaat, grootte, paginatelling en aanmaakdatum indien beschikbaar.

```bash
groupdocs-conversion info annual-review.pdf
```

```text
format:         pdf
size:           291788
pages_count:    10
```

Gebruik `--password` voor beveiligde bronnen.

### list-formats

Geef elk doelindeling weer die de engine kan produceren voor een gegeven invoerdocument, gesplitst in primaire en secundaire doelen.

```bash
groupdocs-conversion list-formats business-plan.docx
```

Gebruik `--password` voor beveiligde bronnen.

### list-all-formats

Print de volledige bron-naar-doel conversiematrix die de engine kent — elk invoerformaat en de doelen waarnaar het kan worden geconverteerd.

```bash
groupdocs-conversion list-all-formats
```

Dit commando neemt geen invoerbestand.

## Global options

Deze opties gelden voor elk commando:

| Optie | Beschrijving |
| :- | :- |
| `--license PATH` | Pas een licentiebestand toe voordat het commando wordt uitgevoerd. |
| `--version` | Print de CLI-versie en sluit af. |
| `--help` | Toon gebruikshulp en sluit af. |

Pas een licentie vooraf toe door `--license` vóór het subcommando te plaatsen:

```bash
groupdocs-conversion --license GroupDocs.Conversion.lic convert business-plan.docx business-plan.pdf
```

De CLI respecteert ook de omgevingsvariabele `GROUPDOCS_LIC_PATH` — als deze is ingesteld, wordt de licentie automatisch toegepast en kun je `--license` weglaten. Zie het onderwerp [Licensing]() voor details.

## Format tokens

`convert` koppelt de uitvoerextensie — of de `--format`-waarde, in kleine letters — aan de bijbehorende conversie‑opties en bestandstype. De ondersteunde tokens zijn:

| Categorie | Tokens |
| :- | :- |
| PDF | `pdf` |
| Tekstverwerking | `doc`, `docx`, `rtf`, `odt`, `txt`, `md` |
| Rekenblad | `xls`, `xlsx`, `xlsm`, `ods`, `csv`, `tsv` |
| Presentatie | `ppt`, `pptx`, `pptm`, `odp` |
| Web | `html`, `htm`, `mhtml` |
| Afbeelding | `jpg`, `jpeg`, `png`, `bmp`, `gif`, `tiff`, `tif`, `webp`, `svg` |
| e‑boek | `epub`, `mobi`, `azw3` |

Een onbekend token zorgt ervoor dat het commando afsluit met code `2` en de lijst met geaccepteerde tokens afdrukt.

## Exit codes

| Code | Betekenis |
| :- | :- |
| `0` | Succes. |
| `2` | Gebruikersfout — onbekend formaat‑token of ontbrekend invoerbestand. |
| `1` | Runtime‑fout — het onderliggende .NET‑exceptiebericht wordt naar de standaardfout geschreven. |

Deze codes maken het CLI gemakkelijk te gebruiken in shell‑scripts en CI‑pijplijnen.

## When to use the Python API instead

Het CLI dekt de veelvoorkomende een‑document‑conversiegevallen. Voor alles daarbuiten — per‑pagina‑callbacks, in‑memory‑streams, watermerk, lettertype of cel‑bereikopties, en multi‑document‑containerhiërarchieën — gebruik je de Python‑API rechtstreeks. Het biedt een rijkere functionaliteit dan de CLI‑vlaggen. Zie de [Developer Guide]() voor de volledige functieverzameling.

## Next Steps

- [Quick Start Guide](): Convert your first document with the Python API.
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Apply a license to remove evaluation limits.
- [Technical Support](): Contact support if you encounter issues.
