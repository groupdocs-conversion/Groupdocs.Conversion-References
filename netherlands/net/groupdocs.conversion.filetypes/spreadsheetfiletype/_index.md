---
title: "SpreadsheetFileType"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Definieert spreadsheet‑documenten. Bevat de volgende bestandstypen Csv./spreadsheetfiletype/csv Fods./spreadsheetfiletype/fods Ods./spreadsheetfiletype/ods Ots./spreadsheetfiletype/ots Tsv./spreadsheetfiletype/tsv Xlam./spreadsheetfiletype/xlam Xls./spreadsheetfiletype/xls Xlsb./spreadsheetfiletype/xlsb Xlsm./spreadsheetfiletype/xlsm Xlsx./spreadsheetfiletype/xlsx Xlt./spreadsheetfiletype/xlt Xltm./spreadsheetfiletype/xltm Xltx./spreadsheetfiletype/xltx. Meer informatie over spreadsheet‑formaten hierhttps//wiki.fileformat.com/spreadsheet."
type: docs
weight: 1240
url: /nl/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

Definieert spreadsheet‑documenten. Bevat de volgende bestandstypen: [`Csv`](./csv), [`Fods`](./fods), [`Ods`](./ods), [`Ots`](./ots), [`Tsv`](./tsv), [`Xlam`](./xlam), [`Xls`](./xls), [`Xlsb`](./xlsb), [`Xlsm`](./xlsm), [`Xlsx`](./xlsx), [`Xlt`](./xlt), [`Xltm`](./xltm), [`Xltx`](./xltx). Meer informatie over spreadsheet‑formaten [hier](https://wiki.fileformat.com/spreadsheet).

```csharp
public sealed class SpreadsheetFileType : FileType
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | Serialisatie‑constructor |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Bestandstypebeschrijving |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | De bestandsextensie |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | De bestandsfamilie |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Het bestandsformaat |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Vergelijkt het huidige object met een ander. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementeert [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Dient als de standaard hash-functie. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Stringrepresentatie |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | Bestanden met de CSV‑ (Comma Separated Values) extensie vertegenwoordigen platte‑tekstbestanden die gegevensrecords bevatten met door komma’s gescheiden waarden. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/csv). |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF staat voor Data Interchange Format en wordt gebruikt om spreadsheet‑gegevens tussen verschillende toepassingen te importeren/exporteren. Deze omvatten Microsoft Excel, OpenOffice Calc, StarCalc en vele anderen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/dif). |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/flatopc) | Flat OPC Excel is Office Open XML SpreadsheetML opgeslagen in een plat XML‑bestand in plaats van een ZIP‑pakket. |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | Een bestand met de .fods‑extensie is een type OpenDocument Spreadsheet‑formaat dat gegevens opslaat in rijen en kolommen. Het formaat is gespecificeerd als onderdeel van de ODF 1.2‑specificaties die door OASIS zijn gepubliceerd en onderhouden. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/fods). |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | Bestanden met de .numbers‑extensie worden geclassificeerd als spreadsheet‑bestandstype, daarom lijken ze op .xlsx‑bestanden; maar Numbers‑bestanden worden gemaakt met de Apple iWork Numbers‑spreadsheetsoftware. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/spreadsheet/numbers). |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | Bestanden met de ODS‑extensie staan voor het OpenDocument Spreadsheet‑documentformaat dat door de gebruiker bewerkbaar is. Gegevens worden in het ODF‑bestand opgeslagen in rijen en kolommen. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | Een bestand met de .ots‑extensie is een OpenDocument Spreadsheet‑sjabloonbestand dat wordt gemaakt met de Calc‑toepassing die is opgenomen in Apache OpenOffice. De Calc‑software is vergelijkbaar met Excel die beschikbaar is in Microsoft Office. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/ots). |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | Het bestandsformaat SXC (Sun XML Calc) behoort tot een kantoorsuite genaamd OpenOffice.org. Dit formaat voorziet over het algemeen in de spreadsheet‑behoeften van gebruikers, omdat het een op XML gebaseerd spreadsheet‑bestandformaat is. Het SXC‑formaat ondersteunt formules, functies, macro's en grafieken, samen met DataPilot. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/sxc). |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | Een Tab-gescheiden waarden (TSV) bestandsformaat vertegenwoordigt gegevens die met tabs zijn gescheiden in platte-tekstformaat. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/tsv). |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM is een macro-ondersteund add‑in‑bestand dat wordt gebruikt om nieuwe functies aan spreadsheets toe te voegen. Een add‑in is een aanvullend programma dat extra code uitvoert en extra functionaliteit voor spreadsheets biedt. Meer informatie over dit bestandsformaat [hier](https://docs.fileformat.com/spreadsheet/xlam/). |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS staat voor Excel Binary File Format. Dergelijke bestanden kunnen worden gemaakt door Microsoft Excel evenals andere vergelijkbare spreadsheetprogramma's zoals OpenOffice Calc of Apple Numbers. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | XLSB‑bestandsformaat specificeert het Excel Binary File Format, dat een verzameling records en structuren is die de inhoud van een Excel-werkmap definiëren. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM is een type spreadsheet‑bestanden dat macro’s ondersteunt. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX is een bekend formaat voor Microsoft Excel‑documenten dat werd geïntroduceerd door Microsoft met de release van Microsoft Office 2007. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | Bestanden met de extensie .XLT zijn sjabloonbestanden die zijn gemaakt met Microsoft Excel, een spreadsheet‑applicatie die deel uitmaakt van de Microsoft Office‑suite. Microsoft Office 97-2003 ondersteunde het maken van nieuwe XLT‑bestanden en het openen ervan. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | De XLTM‑bestandsextensie vertegenwoordigt bestanden die door Microsoft Excel worden gegenereerd als macro‑ingeschakelde sjabloonbestanden. XLTM‑bestanden lijken op XLTX in structuur, behalve dat de laatste geen macro‑ingeschakelde sjabloonbestanden ondersteunt. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | XLTX‑bestand vertegenwoordigt een Microsoft Excel‑sjabloon dat is gebaseerd op de Office OpenXML‑bestandsformaatspecificaties. Het wordt gebruikt om een standaard sjabloonbestand te maken dat kan worden gebruikt om XLSX‑bestanden te genereren die dezelfde instellingen hebben als gespecificeerd in het XLTX‑bestand. Meer informatie over dit bestandsformaat [hier](https://wiki.fileformat.com/spreadsheet/xltx). |

### Zie ook

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
