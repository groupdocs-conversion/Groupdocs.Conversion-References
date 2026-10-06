---
title: "Kommandoradsgränssnitt"
linkTitle: "Command Line Interface"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Konvertera dokument direkt från terminalen med verktyget groupdocs-conversion för kommandoraden — ingen Python‑skript behövs. Inspektera dokument, lista stödda format och tillämpa en licens, allt från skalet."
type: docs
url: /sv/python-net/guides/command-line-interface/
is_root: false
weight: 120
---


När du installerar paketet `groupdocs-conversion-net` placeras även ett konsol‑skript `groupdocs-conversion` i din `PATH`. Det är ett lätt omslag runt Python‑API‑et, byggt för situationer där det är överdrivet att starta ett Python‑skript — skal‑pipelines, Make‑regler, CI‑steg och engångskonverteringar.

## Prerequisites

CLI‑verktyget levereras med paketet, så ingen extra installation behövs. Se till att `groupdocs-conversion-net` är installerat (se [Quick Start Guide]()), och verifiera sedan att konsol‑skriptet är tillgängligt:

```bash
groupdocs-conversion --version
```

Du bör se paketets version skriven, till exempel `groupdocs-conversion 26.9.0`.

Om kommandot `groupdocs-conversion` inte hittas kan paketets skriptkatalog saknas i din `PATH`. Du kan alltid anropa CLI‑verktyget via Python‑modulen istället: `python -m groupdocs.conversion`. De två är ekvivalenta.

## Commands

CLI‑verktyget erbjuder fyra underkommandon. Kör `groupdocs-conversion --help` för en komplett lista över flaggor, eller `groupdocs-conversion <command> --help` för ett specifikt underkommando.

### convert

Konvertera ett dokument till ett annat format. Måletformatet härleds från filens utdata‑filändelse; ange `--format` för att åsidosätta det.

```bash
# Filändelsen bestämmer målformatet
groupdocs-conversion convert business-plan.docx business-plan.pdf

# Åsidosätt formatet när utdatafilens namn saknar en användbar filändelse
groupdocs-conversion convert business-plan.docx output.bin --format pdf

# Konvertera en enskild sida (1‑indexerad) — användbart för rastermål
groupdocs-conversion convert annual-review.pdf page1.png --page 1 --count 1

# Öppna en lösenordsskyddad källa
groupdocs-conversion convert protected.docx protected.pdf --password "secret"
```

| Alternativ | Beskrivning |
| :- | :- |
| `--format` | Målförmatstoken (åsidosätter utdatafilens ändelse). |
| `--password` | Lösenord för ett skyddat källdokument. |
| `--page` | Första sidan att konvertera, 1‑indexerad. |
| `--count` | Antal sidor att konvertera. |

Vid lyckat utförande skriver kommandot ut sökvägen till resultatet och avslutas med kod `0`.

### info

Skriv ut grundläggande information om ett dokument — format, storlek, sidantal och skapelsedatum när det finns tillgängligt.

```bash
groupdocs-conversion info annual-review.pdf
```

```text
format:         pdf
size:           291788
pages_count:    10
```

Använd `--password` för skyddade källor.

### list-formats

Lista alla målformat som motorn kan producera för ett givet indokument, uppdelade i primära och sekundära mål.

```bash
groupdocs-conversion list-formats business-plan.docx
```

Använd `--password` för skyddade källor.

### list-all-formats

Skriv ut hela käll‑till‑mål konverteringsmatrisen som motorn känner till — varje indatformat och de mål den kan konverteras till.

```bash
groupdocs-conversion list-all-formats
```

Detta kommando tar ingen indatafil.

## Global options

Dessa alternativ gäller för alla kommandon:

| Alternativ | Beskrivning |
| :- | :- |
| `--license PATH` | Applicera en licensfil innan kommandot körs. |
| `--version` | Skriv ut CLI‑versionen och avsluta. |
| `--help` | Visa användningshjälp och avsluta. |

Applicera en licens i förväg genom att placera `--license` före underkommandot:

```bash
groupdocs-conversion --license GroupDocs.Conversion.lic convert business-plan.docx business-plan.pdf
```

CLI:n respekterar också miljövariabeln `GROUPDOCS_LIC_PATH` — om den är satt appliceras licensen automatiskt och du kan utelämna `--license`. Se ämnet [Licensing]() för detaljer.

## Format tokens

`convert` mappar utökningen på utdata — eller värdet `--format`, i gemener — till motsvarande konverteringsalternativ och filtyp. De stödjade tokenarna är:

| Kategori | Tokenar |
| :- | :- |
| PDF | `pdf` |
| Ordbehandling | `doc`, `docx`, `rtf`, `odt`, `txt`, `md` |
| Kalkylblad | `xls`, `xlsx`, `xlsm`, `ods`, `csv`, `tsv` |
| Presentation | `ppt`, `pptx`, `pptm`, `odp` |
| Webb | `html`, `htm`, `mhtml` |
| Bild | `jpg`, `jpeg`, `png`, `bmp`, `gif`, `tiff`, `tif`, `webp`, `svg` |
| eBok | `epub`, `mobi`, `azw3` |

En okänd token får kommandot att avsluta med kod `2` och skriva ut listan över accepterade token.

## Exit codes

| Kod | Betydelse |
| :- | :- |
| `0` | Lyckat. |
| `2` | Användarfel — okänd format‑token eller saknad indatafil. |
| `1` | Körfel — det underliggande .NET‑undantagsmeddelandet skrivs ut till standardfel. |

Dessa koder gör det enkelt att grena CLI i skal‑skript och CI‑pipelines.

## When to use the Python API instead

CLI:n täcker de vanliga enkeldokument‑konverteringsfallen. För allt utöver det — per‑sid‑återuppringningar, minnesströmmar, vattenstämpel, teckensnitt eller cell‑intervallalternativ, samt flerdokument‑behållar‑hierarkier — använd Python‑API:n direkt. Den erbjuder ett rikare gränssnitt än CLI‑flaggorna. Se [Developer Guide]() för hela funktionsuppsättningen.

## Next Steps

- [Quick Start Guide](): Convert your first document with the Python API.
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Apply a license to remove evaluation limits.
- [Technical Support](): Contact support if you encounter issues.
