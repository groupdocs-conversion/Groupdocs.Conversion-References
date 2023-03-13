---
title: SpreadsheetLoadOptions
second_title: GroupDocs.Conversion voor .NET API-referentie
description: Opties voor het laden van spreadsheetdocumenten.
type: docs
weight: 2260
url: /nl/net/groupdocs.conversion.options.load/spreadsheetloadoptions/
---
## SpreadsheetLoadOptions class

Opties voor het laden van spreadsheetdocumenten.

```csharp
public class SpreadsheetLoadOptions : LoadOptions
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | Initialiseert nieuw exemplaar van[`SpreadsheetLoadOptions`](../spreadsheetloadoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Of de beperking van het Excel-bestand wordt gecontroleerd wanneer de gebruiker cellen-gerelateerde objecten wijzigt. Excel staat bijvoorbeeld niet toe dat een tekenreekswaarde langer is dan 32K. Als u een waarde invoert die langer is dan 32K en deze eigenschap waar is, krijgt u een uitzondering. Als deze eigenschap onwaar is, accepteren we uw ingevoerde tekenreekswaarde als de waarde van de cel, zodat u later de volledige tekenreekswaarde kunt uitvoeren voor andere bestandsindelingen, zoals CSV. Als u echter een dergelijke waarde hebt ingesteld die ongeldig is voor de Excel-bestandsindeling, moet u de werkmap later niet als Excel-bestandsindeling opslaan. Anders kan er een onverwachte fout optreden voor het gegenereerde Excel-bestand. |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Converteer een specifiek bereik bij het converteren naar een ander formaat dan een spreadsheet. Voorbeeld: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Haal de systeemcultuurinformatie op of stel deze in op het moment dat het bestand wordt geladen |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Standaardlettertype voor spreadsheetdocument. Het volgende lettertype wordt gebruikt als een lettertype ontbreekt. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Vervang specifieke lettertypen bij het converteren van een spreadsheetdocument. |
| [Format](../../groupdocs.conversion.options.load/spreadsheetloadoptions/format) { get; set; } | Type documentbestand invoeren. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Type documentbestand invoeren. |
| [HideComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/hidecomments) { get; set; } | Opmerkingen verbergen. |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | Als OnePagePerSheet waar is, wordt de inhoud van het blad geconverteerd naar één pagina in het PDF-document. Standaardwaarde is waar. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | Indien waar en converteren naar pdf, wordt de conversie geoptimaliseerd voor een betere bestandsgrootte dan afdrukkwaliteit. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Stel wachtwoord in om beveiligd document op te heffen. |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | Lijst met te converteren bladindexen. De indexen moeten op nul zijn gebaseerd |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | Bladnaam om te converteren |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Toon rasterlijnen bij het converteren van Excel-bestanden. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Toon verborgen bladen bij het converteren van Excel-bestanden. |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | Slaat lege rijen en kolommen over bij het converteren. Standaard is True. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | Kloont huidige instantie. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [LoadOptions](../loadoptions)
* naamruimte [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
