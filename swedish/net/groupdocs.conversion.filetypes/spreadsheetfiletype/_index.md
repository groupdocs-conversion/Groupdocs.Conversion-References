---
title: "SpreadsheetFileType"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Definierar kalkylbladsdokument. Inkluderar följande filtyper Csv./spreadsheetfiletype/csv Fods./spreadsheetfiletype/fods Ods./spreadsheetfiletype/ods Ots./spreadsheetfiletype/ots Tsv./spreadsheetfiletype/tsv Xlam./spreadsheetfiletype/xlam Xls./spreadsheetfiletype/xls Xlsb./spreadsheetfiletype/xlsb Xlsm./spreadsheetfiletype/xlsm Xlsx./spreadsheetfiletype/xlsx Xlt./spreadsheetfiletype/xlt Xltm./spreadsheetfiletype/xltm Xltx./spreadsheetfiletype/xltx. Läs mer om kalkylbladsformat härhttps//wiki.fileformat.com/spreadsheet."
type: docs
weight: 1240
url: /sv/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

Definierar kalkylbladsdokument. Inkluderar följande filtyper: [`Csv`](./csv), [`Fods`](./fods), [`Ods`](./ods), [`Ots`](./ots), [`Tsv`](./tsv), [`Xlam`](./xlam), [`Xls`](./xls), [`Xlsb`](./xlsb), [`Xlsm`](./xlsm), [`Xlsx`](./xlsx), [`Xlt`](./xlt), [`Xltm`](./xltm), [`Xltx`](./xltx). Läs mer om kalkylbladsformat [här](https://wiki.fileformat.com/spreadsheet).

```csharp
public sealed class SpreadsheetFileType : FileType
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | Serialiseringskonstruktor |

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
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | Filer med CSV (Comma Separated Values)-ändelse representerar rena textfiler som innehåller dataposter med kommaseparerade värden. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/csv). |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF står för Data Interchange Format som används för att importera/exportera kalkylbladsdata mellan olika program. Dessa inkluderar Microsoft Excel, OpenOffice Calc, StarCalc och många andra. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/dif). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/flatopc) | Flat OPC Excel är Office Open XML SpreadsheetML lagrat i en platt XML-fil istället för ett ZIP-paket. |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | En fil med .fods‑ändelse är en typ av OpenDocument Spreadsheet-dokumentformat som lagrar data i rader och kolumner. Formatet specificeras som en del av ODF 1.2‑specifikationerna som publicerats och underhålls av OASIS. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/fods). |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | Filer med .numbers‑ändelse klassificeras som kalkylbladsfiltyp, därför liknar de .xlsx‑filerna; men Numbers-filerna skapas med Apples iWork Numbers kalkylbladsprogram. Läs mer om detta filformat [här](https://docs.fileformat.com/spreadsheet/numbers). |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | Filer med ODS‑ändelse står för OpenDocument Spreadsheet Document-format som kan redigeras av användaren. Data lagras i ODF-filen i rader och kolumner. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | En fil med .ots‑ändelse är en OpenDocument Spreadsheet‑mallfil som skapas med Calc‑programvaran som ingår i Apache OpenOffice. Calc‑programvaran liknar Excel som finns i Microsoft Office. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/ots). |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | Filformatet SXC(Sun XML Calc) tillhör en kontorssvit som heter OpenOffice.org. Detta format hanterar generellt kalkylbladsbehoven hos användare eftersom det är ett XML‑baserat kalkylbladsfilformat. SXC‑formatet stöder formler, funktioner, makron och diagram tillsammans med DataPilot. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/sxc). |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | Ett Tab‑separerade Värden (TSV) filformat representerar data separerade med tabbar i ett vanligt textformat. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/tsv). |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM är en makroaktiverad tilläggsfil som används för att lägga till nya funktioner i kalkylblad. Ett tillägg är ett kompletterande program som kör extra kod och ger ytterligare funktionalitet för kalkylblad. Läs mer om detta filformat [här](https://docs.fileformat.com/spreadsheet/xlam/). |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS representerar Excel Binary File Format. Sådana filer kan skapas av Microsoft Excel såväl som andra liknande kalkylbladsprogram som OpenOffice Calc eller Apple Numbers. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | XLSB‑filformatet specificerar Excel Binary File Format, vilket är en samling poster och strukturer som specificerar innehållet i en Excel‑arbetsbok. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM är en typ av kalkylbladsfiler som stödjer makron. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX är ett välkänt format för Microsoft Excel‑dokument som introducerades av Microsoft med lanseringen av Microsoft Office 2007. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | Filer med .XLT‑extension är mallfiler skapade med Microsoft Excel, som är ett kalkylbladsprogram som ingår i Microsoft Office‑sviten. Microsoft Office 97‑2003 stödde att skapa nya XLT‑filer samt att öppna dem. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | XLTM‑filändelsen representerar filer som genereras av Microsoft Excel som makroaktiverade mallfiler. XLTM‑filer liknar XLTX i struktur förutom att den senare inte stödjer att skapa mallfiler med makron. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | XLTX‑filen representerar Microsoft Excel‑mallar som är baserade på Office OpenXML‑filformatspecifikationerna. Den används för att skapa en standardmallfil som kan utnyttjas för att generera XLSX‑filer som har samma inställningar som specificeras i XLTX‑filen. Läs mer om detta filformat [här](https://wiki.fileformat.com/spreadsheet/xltx). |

### Se även

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
