---
title: WordProcessingFileType
second_title: GroupDocs.Conversion for .NET API Referens
description: Definierar ordbehandlingsfiler som innehåller användarinformation i vanlig text eller RTFformat. Ett filformat med vanlig text innehåller oformaterad text och inga teckensnitt eller sidinställningar etc. kan tillämpas. Däremot tillåter ett filformat med rik text formateringsalternativ som att ställa in typsnittstyp stilar fet kursiv understruken etc. sidmarginaler rubriker punkter och siffror och flera andra formateringsfunktioner. Inkluderar följande filtyper Doc./wordprocessingfiletype/doc  Docm./wordprocessingfiletype/docm  Docx./wordprocessingfiletype/docx  Dot./wordprocessingfiletype/dot  Dotm./wordprocessingfiletype/dotm  Dotx./wordprocessingfiletype/dotx  Mobi  Odt./wordprocessingfiletype/odt  Ott./wordprocessingfiletype/ott  Rtf./wordprocessingfiletype/rtf  Txt./wordprocessingfiletype/txt . Md./wordprocessingfiletype/md . Log . Läs mer om ordbehandlingsformathärhttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 1090
url: /sv/net/groupdocs.conversion.filetypes/wordprocessingfiletype/
---
## WordProcessingFileType class

Definierar ordbehandlingsfiler som innehåller användarinformation i vanlig text eller RTF-format. Ett filformat med vanlig text innehåller oformaterad text och inga teckensnitt eller sidinställningar etc. kan tillämpas. Däremot tillåter ett filformat med rik text formateringsalternativ som att ställa in typsnittstyp, stilar (fet, kursiv, understruken, etc.), sidmarginaler, rubriker, punkter och siffror och flera andra formateringsfunktioner. Inkluderar följande filtyper: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , Mobi , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`Txt`](./txt) . [`Md`](./md) . Log . Läs mer om ordbehandlingsformat[här](https://wiki.fileformat.com/word-processing) .

```csharp
public sealed class WordProcessingFileType : FileType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [WordProcessingFileType](wordprocessingfiletype)() | Serialiseringskonstruktor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Filtypsbeskrivning |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Filtillägget |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Filfamiljen |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Filformatet |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Jämför aktuellt objekt med annat. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Bestämmer om två objektinstanser är lika. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Fungerar som standard hash-funktion. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Strängrepresentation |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [Doc](../../groupdocs.conversion.filetypes/wordprocessingfiletype/doc) | Filer med filtillägget .doc representerar dokument som genererats av Microsoft Word eller andra ordbehandlingsdokument i binärt filformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docm) | DOCM-filer är Microsoft Word 2007 eller högre genererade dokument med möjlighet att köra makron. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/docx) | DOCX är ett välkänt format för Microsoft Word-dokument. Introducerad från 2007 med lanseringen av Microsoft Office 2007, ändrades strukturen för detta nya dokumentformat från vanligt binärt till en kombination av XML och binära filer. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dot) | Filer med filtillägget .DOT är mallfiler skapade av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOC- eller DOCX-filer. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotm) | En fil med DOTM-tillägget representerar en mallfil skapad med Microsoft Word 2007 eller högre. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.conversion.filetypes/wordprocessingfiletype/dotx) | Filer med DOTX-tillägg är mallfiler skapade av Microsoft Word för att ha förformaterade inställningar för generering av ytterligare DOCX-filer. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [Md](../../groupdocs.conversion.filetypes/wordprocessingfiletype/md) | Textfiler skapade med Markdown-språkdialekter sparas med filtillägget .MD eller .MARKDOWN. MD-filer sparas i vanligt textformat som använder Markdown-språk som också inkluderar inline textsymboler, som definierar hur en text kan formateras som indrag, tabellformatering, typsnitt och rubriker. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/md) . |
| static readonly [Odt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/odt) | ODT-filer är typ av dokument skapade med ordbehandlingsprogram som är baserade på OpenDocument Text File-format. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.conversion.filetypes/wordprocessingfiletype/ott) | Filer med OTT-tillägg representerar malldokument som genereras av applikationer i enlighet med OASIS OpenDocument-standardformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.conversion.filetypes/wordprocessingfiletype/rtf) | Introducerat och dokumenterat av Microsoft, Rich Text Format (RTF) representerar en metod för att koda formaterad text och grafik för användning i applikationer. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [Txt](../../groupdocs.conversion.filetypes/wordprocessingfiletype/txt) | En fil med filtillägget .TXT representerar ett textdokument som innehåller vanlig text i form av rader. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/txt) . |

### Se även

* class [FileType](../filetype)
* namnutrymme [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* hopsättning [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
