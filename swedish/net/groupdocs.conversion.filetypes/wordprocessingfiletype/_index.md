---
title: "WordProcessingFileType"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Definierar ordbehandlingsfiler som innehåller användarinformation i vanlig text eller rik textformat. Ett vanligt textfilformat innehåller oformaterad text och inga teckensnitt eller sidinställningar etc. kan tillämpas. I kontrast tillåter ett rik textfilformat formateringsalternativ såsom att ställa in teckensnittstyper, stilar, fet, kursiv, understruken, etc., sidmarginaler, rubriker, punktlistor och nummer samt flera andra formateringsfunktioner. Inkluderar följande filtyper Doc./wordprocessingfiletype/doc Docm./wordprocessingfiletype/docm Docx./wordprocessingfiletype/docx Dot./wordprocessingfiletype/dot Dotm./wordprocessingfiletype/dotm Dotx./wordprocessingfiletype/dotx Odt./wordprocessingfiletype/odt Ott./wordprocessingfiletype/ott Rtf./wordprocessingfiletype/rtf Txt./wordprocessingfiletype/txt. Md./wordprocessingfiletype/md. Läs mer om ordbehandlingsformat härhttps//wiki.fileformat.com/wordprocessing."
type: docs
weight: 1280
url: /sv/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Definierar ordbehandlingsfiler som innehåller användarinformation i vanlig text eller rik textformat. Ett vanligt textfilformat innehåller oformaterad text och inga teckensnitt eller sidinställningar etc. kan tillämpas. I kontrast tillåter ett rik textfilformat formateringsalternativ såsom att ställa in teckensnittstyper, stilar (fet, kursiv, understruken, etc.), sidmarginaler, rubriker, punktlistor och nummer, samt flera andra formateringsfunktioner. Inkluderar följande filtyper: [`Doc`](./doc), [`Docm`](./docm), [`Docx`](./docx), [`Dot`](./dot), [`Dotm`](./dotm), [`Dotx`](./dotx), [`Odt`](./odt), [`Ott`](./ott), [`Rtf`](./rtf), [`Txt`](./txt). [`Md`](./md). Läs mer om ordbehandlingsformat [här](https://wiki.fileformat.com/word-processing).

```csharp
public sealed class WordProcessingFileType : FileType
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | Serialiseringskonstruktor |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Filtypbeskrivning |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Filändelsen |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Filfamiljen |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Filformatet |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Jämför aktuellt objekt med annat. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementerar [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Fungerar som standardhash-funktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Strängrepresentation |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | Filer med .doc‑tillägg representerar dokument som genereras av Microsoft Word eller andra ordbehandlingsdokument i binärt filformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | DOCM‑filer är dokument som genererats av Microsoft Word 2007 eller senare med möjlighet att köra makron. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX är ett välkänt format för Microsoft Word‑dokument. Introducerat från 2007 med lanseringen av Microsoft Office 2007 förändrades strukturen för detta nya dokumentformat från ren binär till en kombination av XML‑ och binära filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | Filer med .DOT‑tillägg är mallfiler som skapats av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOC‑ eller DOCX‑filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | En fil med DOTM‑tillägg representerar en mallfil skapad med Microsoft Word 2007 eller senare. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | Filer med DOTX‑tillägg är mallfiler som skapats av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOCX‑filer. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/flatopc) | Flat OPC Word är Office Open XML WordprocessingML lagrat i en platt XML‑fil istället för ett ZIP‑paket. |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Textfiler som skapats med Markdown-språkdialekter sparas med filändelsen .MD eller .MARKDOWN. MD-filer sparas i vanligt textformat som använder Markdown-språket och som även inkluderar inline‑textsymboler, vilket definierar hur en text kan formateras såsom indrag, tabellformat, teckensnitt och rubriker. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/md). |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | ODT-filer är en typ av dokument som skapats med ordbehandlingsprogram baserade på OpenDocument Text File-formatet. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | Filer med OTT‑ändelse representerar mall‑dokument som genererats av program i enlighet med OASIS' OpenDocument‑standardformatet. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Introducerat och dokumenterat av Microsoft, Rich Text Format (RTF) representerar en metod för att koda formaterad text och grafik för användning i program. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | En fil med .TXT‑ändelse representerar ett textdokument som innehåller vanlig text i form av rader. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/txt). |

### Se även

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
