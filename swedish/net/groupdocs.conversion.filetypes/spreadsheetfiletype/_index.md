---
title: SpreadsheetFileType
second_title: GroupDocs.Conversion for .NET API Referens
description: Definierar kalkylarksdokument. Inkluderar följande filtyper Csv./spreadsheetfiletype/csv  Fods./spreadsheetfiletype/fods  Ods./spreadsheetfiletype/ods  Ots./spreadsheetfiletype/ots  Tsv./spreadsheetfiletype/tsv  Xlam./spreadsheetfiletype/xlam  Xls./spreadsheetfiletype/xls  Xlsb./spreadsheetfiletype/xlsb  Xlsm./spreadsheetfiletype/xlsm  Xlsx./spreadsheetfiletype/xlsx  Xlt./spreadsheetfiletype/xlt  Xltm./spreadsheetfiletype/xltm  Xltx./spreadsheetfiletype/xltx . Läs mer om kalkylarksformathärhttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 1050
url: /sv/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

Definierar kalkylarksdokument. Inkluderar följande filtyper: [`Csv`](./csv) , [`Fods`](./fods) , [`Ods`](./ods) , [`Ots`](./ots) , [`Tsv`](./tsv) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . Läs mer om kalkylarksformat[här](https://wiki.fileformat.com/spreadsheet) .

```csharp
public sealed class SpreadsheetFileType : FileType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | Serialiseringskonstruktor |

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
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | Filer med tillägget CSV (Comma Separated Values) representerar vanliga textfiler som innehåller dataposter med kommaseparerade värden. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF står för Data Interchange Format som används för att importera/exportera kalkylbladsdata mellan olika applikationer. Dessa inkluderar Microsoft Excel, OpenOffice Calc, StarCalc och många andra. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/dif) . |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | En fil med filtillägget .fods är en typ av OpenDocument Spreadsheet-dokumentformat som lagrar data i rader och kolumner. Formatet anges som en del av ODF 1.2-specifikationerna publicerade och underhållna av OASIS. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/fods) . |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | Filerna med tillägget .numbers klassificeras som kalkylbladsfiltyp, det är därför de liknar .xlsx-filerna; men Numbers-filerna skapas med hjälp av Apple iWork Numbers-kalkylprogram. Läs mer om det här filformatet[här](https://docs.fileformat.com/spreadsheet/numbers) . |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | Filer med ODS-tillägg står för OpenDocument Spreadsheet Document-format som kan redigeras av användaren. Data lagras i ODF-filen i rader och kolumner. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | En fil med filtillägget .ots är en OpenDocument Spreadsheet Template-fil som skapas med Calc-programvaran som ingår i Apache OpenOffice. Calc-programvaran liknar Excel som finns i Microsoft Office. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/ots) . |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | Filformatet SXC(Sun XML Calc) tillhör en kontorssvit som heter OpenOffice.org. Detta format hanterar i allmänhet användarnas kalkylbladsbehov eftersom det är ett XML-baserat kalkylarksfilformat. SXC-format stöder formler, funktioner, makron och diagram tillsammans med DataPilot. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/sxc) . |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | Filformatet Tab-Separated Values (TSV) representerar data separerade med flikar i vanligt textformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM är en makroaktiverad tilläggsfil som används för att lägga till nya funktioner i kalkylblad. Ett tillägg är ett tilläggsprogram som kör ytterligare kod och ger ytterligare funktionalitet för kalkylblad. Läs mer om detta filformat[här](https://docs.fileformat.com/spreadsheet/xlam/) . |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS representerar det binära filformatet i Excel. Sådana filer kan skapas av Microsoft Excel såväl som andra liknande kalkylprogram som OpenOffice Calc eller Apple Numbers. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | XLSB-filformatet anger det binära filformatet för Excel, som är en samling poster och strukturer som anger innehållet i Excel-arbetsboken. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM är en typ av kalkylbladsfiler som stöder makron. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX är ett välkänt format för Microsoft Excel-dokument som introducerades av Microsoft med lanseringen av Microsoft Office 2007. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | Filer med filtillägget .XLT är mallfiler skapade med Microsoft Excel som är ett kalkylprogram som kommer som en del av Microsoft Office-paketet. Microsoft Office 97-2003 stödde att skapa nya XLT-filer samt att öppna dessa. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | Filtillägget XLTM representerar filer som genereras av Microsoft Excel som makroaktiverade mallfiler. XLTM-filer liknar XLTX i annan struktur än att de senare inte stöder att skapa mallfiler med makron. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | XLTX-filen representerar Microsoft Excel-mall som är baserad på Office OpenXML-filformatspecifikationerna. Den används för att skapa en standardmallfil som kan användas för att generera XLSX-filer som uppvisar samma inställningar som anges i XLTX-filen. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xltx) . |

### Se även

* class [FileType](../filetype)
* namnutrymme [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* hopsättning [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
