---
title: SpreadsheetFileType
second_title: GroupDocs.Conversion voor .NET API-referentie
description: Definieert spreadsheetdocumenten. Bevat de volgende bestandstypen Csv./spreadsheetfiletype/csv  Fods./spreadsheetfiletype/fods  Ods./spreadsheetfiletype/ods  Ots./spreadsheetfiletype/ots  Tsv./spreadsheetfiletype/tsv  Xlam./spreadsheetfiletype/xlam  Xls./spreadsheetfiletype/xls  Xlsb./spreadsheetfiletype/xlsb  Xlsm./spreadsheetfiletype/xlsm  Xlsx./spreadsheetfiletype/xlsx  Xlt./spreadsheetfiletype/xlt  Xltm./spreadsheetfiletype/xltm  Xltx./spreadsheetfiletype/xltx . Meer informatie over spreadsheetindelingenhierhttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 1050
url: /nl/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

Definieert spreadsheetdocumenten. Bevat de volgende bestandstypen: [`Csv`](./csv) , [`Fods`](./fods) , [`Ods`](./ods) , [`Ots`](./ots) , [`Tsv`](./tsv) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . Meer informatie over spreadsheetindelingen[hier](https://wiki.fileformat.com/spreadsheet) .

```csharp
public sealed class SpreadsheetFileType : FileType
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | Serialisatie-constructor |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Bestandstype omschrijving |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | De bestandsextensie |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | De bestandsfamilie |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Het bestandsformaat |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Vergelijkt huidige object met andere. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Dient als de standaard hash-functie. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Tekenreeksweergave |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | Bestanden met de extensie CSV (Comma Separated Values) staan voor platte tekstbestanden die gegevensrecords bevatten met door komma's gescheiden waarden. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/spreadsheet/csv) . |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF staat voor Data Interchange Format dat wordt gebruikt om spreadsheetgegevens tussen verschillende applicaties te importeren/exporteren. Deze omvatten Microsoft Excel, OpenOffice Calc, StarCalc en vele anderen. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/spreadsheet/dif) . |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | Een bestand met de extensie .fods is een type OpenDocument Spreadsheet-documentindeling waarin gegevens in rijen en kolommen worden opgeslagen. De indeling is gespecificeerd als onderdeel van de ODF 1.2-specificaties die zijn gepubliceerd en onderhouden door OASIS. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/spreadsheet/fods) . |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | De bestanden met de extensie .numbers zijn geclassificeerd als spreadsheetbestandstype, daarom lijken ze op de .xlsx-bestanden; maar de Numbers-bestanden worden gemaakt met Apple iWork Numbers-spreadsheetsoftware. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/spreadsheet/numbers) . |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | Bestanden met ODS-extensie staan voor OpenDocument Spreadsheet Document-indeling die door de gebruiker kan worden bewerkt. Gegevens worden in het ODF-bestand opgeslagen in rijen en kolommen. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | Een bestand met de extensie .ots is een OpenDocument Spreadsheet-sjabloonbestand dat is gemaakt met de Calc-toepassingssoftware die is opgenomen in Apache OpenOffice. Calc-toepassingssoftware is vergelijkbaar met Excel die beschikbaar is in Microsoft Office. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/spreadsheet/ots) . |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | Het bestandsformaat SXC (Sun XML Calc) behoort tot een kantoorsuite genaamd OpenOffice.org. Dit formaat houdt over het algemeen rekening met de spreadsheetbehoeften van gebruikers, aangezien het een op XML gebaseerd spreadsheetbestandsformaat is. SXC-indeling ondersteunt formules, functies, macro's en grafieken samen met DataPilot. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/spreadsheet/sxc) . |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | Een door tabs gescheiden waarden (TSV)-bestandsindeling vertegenwoordigt gegevens gescheiden door tabs in tekst zonder opmaak. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/spreadsheet/tsv) . |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM is een macro-enabled add-in-bestand dat wordt gebruikt om nieuwe functies aan spreadsheets toe te voegen. Een invoegtoepassing is een aanvullend programma dat aanvullende code uitvoert en extra functionaliteit biedt voor spreadsheets. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/spreadsheet/xlam/) . |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS staat voor Excel binair bestandsformaat. Dergelijke bestanden kunnen worden gemaakt door Microsoft Excel en andere vergelijkbare spreadsheetprogramma's zoals OpenOffice Calc of Apple Numbers. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | XLSB-bestandsindeling specificeert de Excel binaire bestandsindeling, een verzameling records en structuren die de inhoud van de Excel-werkmap specificeren. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM is een type Spreadsheet-bestanden dat macro's ondersteunt. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX is een bekende indeling voor Microsoft Excel-documenten die door Microsoft is geïntroduceerd met de release van Microsoft Office 2007. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | Bestanden met de extensie .XLT zijn sjabloonbestanden die zijn gemaakt met Microsoft Excel, een spreadsheettoepassing die deel uitmaakt van de Microsoft Office-suite. Microsoft Office 97-2003 ondersteunde het maken van nieuwe XLT-bestanden en het openen ervan. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | De XLTM-bestandsextensie vertegenwoordigt bestanden die door Microsoft Excel worden gegenereerd als sjabloonbestanden met macro's. XLTM-bestanden lijken qua structuur op XLTX, behalve dat de laatste geen ondersteuning biedt voor het maken van sjabloonbestanden met macro's. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | XLTX-bestand vertegenwoordigt Microsoft Excel-sjabloon die is gebaseerd op de Office OpenXML-bestandsformaatspecificaties. Het wordt gebruikt om een standaard sjabloonbestand te maken dat kan worden gebruikt om XLSX-bestanden te genereren met dezelfde instellingen als gespecificeerd in het XLTX-bestand. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/spreadsheet/xltx) . |

### Zie ook

* class [FileType](../filetype)
* naamruimte [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
