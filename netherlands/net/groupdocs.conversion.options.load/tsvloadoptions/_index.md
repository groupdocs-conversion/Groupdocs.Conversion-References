---
title: "TsvLoadOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Opties voor het laden van Tsv-documenten."
type: docs
weight: 2850
url: /nl/net/groupdocs.conversion.options.load/tsvloadoptions/
---
## TsvLoadOptions class

Opties voor het laden van Tsv-documenten.

```csharp
public sealed class TsvLoadOptions : SpreadsheetLoadOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [TsvLoadOptions](tsvloadoptions)() | Initialiseert een nieuwe instantie van de klasse [`TsvLoadOptions`](../tsvloadoptions). |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AllColumnsInOnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/allcolumnsinonepagepersheet) { get; set; } | Als AllColumnsInOnePagePerSheet waar is, wordt de inhoud van alle kolommen van één blad naar slechts één pagina in het resultaat geëxporteerd. De breedte van het papierformaat van pagesetup wordt ongeldig, maar de andere instellingen van pagesetup blijven van kracht. |
| [AutoFitRows](../../groupdocs.conversion.options.load/spreadsheetloadoptions/autofitrows) { get; set; } | Past alle rijen automatisch aan bij het converteren |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Of de beperkingen van een Excel‑bestand worden gecontroleerd wanneer de gebruiker gerelateerde objecten van cellen wijzigt. Bijvoorbeeld, Excel staat niet toe dat een tekenreeks langer dan 32 KB wordt ingevoerd. Wanneer u een waarde langer dan 32 KB invoert, krijgt u een Exception als deze eigenschap waar is. Als deze eigenschap onwaar is, accepteren we uw ingevoerde tekenreeks als de celwaarde, zodat u later de volledige tekenreeks kunt exporteren naar andere bestandsformaten zoals CSV. Als u echter een waarde instelt die ongeldig is voor het Excel‑formaat, moet u het werkboek later niet opslaan als Excel‑bestand. Anders kan er een onverwachte fout optreden in het gegenereerde Excel‑bestand. |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearbuiltindocumentproperties) { get; set; } | Verwijdert ingebouwde metagegevens‑eigenschappen uit het document. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearcustomdocumentproperties) { get; set; } | Verwijdert aangepaste metagegevens‑eigenschappen uit het document. |
| [ColumnsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/columnsperpage) { get; set; } | Splits een werkblad in pagina's per kolom. Standaard is 0, geen paginering. |
| [ConvertOwned](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowned) { get; set; } | Implementeert [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Standaard is false |
| [ConvertOwner](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowner) { get; set; } | Implementeert [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Standaard is true |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Converteer een specifiek bereik bij het converteren naar een ander formaat dan spreadsheet. Voorbeeld: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Haal de systeem‑cultuurinfo op of stel deze in op het moment dat het bestand wordt geladen |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Standaardlettertype voor spreadsheet‑document. Het volgende lettertype wordt gebruikt als een lettertype ontbreekt. |
| [Depth](../../groupdocs.conversion.options.load/spreadsheetloadoptions/depth) { get; set; } | Implementeert [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Standaard: 1 |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Vervang specifieke lettertypen bij het converteren van een spreadsheet‑document. |
| [Format](../../groupdocs.conversion.options.load/tsvloadoptions/format) { get; } | Invoerdocument bestandstype. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Invoerdocument bestandstype. |
| [IgnoreFormulaCalculationErrors](../../groupdocs.conversion.options.load/spreadsheetloadoptions/ignoreformulacalculationerrors) { get; set; } | Geeft aan of formule‑berekeningsfouten moeten worden genegeerd. De fout kan een niet‑ondersteunde functie, externe koppelingen, enz. zijn. Standaard is onwaar. |
| [MarginSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/marginsettings) { get; set; } | Instellingen voor paginamarges |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | Als OnePagePerSheet waar is, wordt de inhoud van het blad geconverteerd naar één pagina in het PDF‑document. Standaardwaarde is waar. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | Als waar en bij het converteren naar PDF, wordt de conversie geoptimaliseerd voor een kleinere bestandsgrootte ten koste van de afdrukkwaliteit. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Stel wachtwoord in om een beschermd document te ontgrendelen. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/spreadsheetloadoptions/preservedocumentstructure) { get; set; } | Bepaalt of de documentstructuur behouden moet blijven bij het converteren naar PDF (standaard is false). |
| [PrintComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/printcomments) { get; set; } | Geeft weer hoe opmerkingen worden afgedrukt met het blad. Standaard is PrintNoComments. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/resetfontfolders) { get; set; } | Reset lettertype‑mappen vóór het laden van het document |
| [RowsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/rowsperpage) { get; set; } | Splits een werkblad in pagina's per rij. Standaard is 0, geen paginering. |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | Lijst van blad‑indexen om te converteren. De indexen moeten nulgebaseerd zijn |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | Bladnaam om te converteren |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Toon rasterlijnen bij het converteren van Excel‑bestanden. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Toon verborgen bladen bij het converteren van Excel‑bestanden. |
| [SizeSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sizesettings) { get; set; } | Instellingen voor paginagrootte |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | Slaat lege rijen en kolommen over bij het converteren. Standaard is waar. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipexternalresources) { get; set; } | Implementeert [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [SkipFooters](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipfooters) { get; set; } | Sla voetteksten over bij het converteren van spreadsheet‑documenten. Standaard: onwaar. |
| [SkipHeaders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipheaders) { get; set; } | Sla kopteksten over bij het converteren van spreadsheet‑documenten. Standaard: onwaar. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/whitelistedresources) { get; set; } | Implementeert [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | Kloont de huidige instantie. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
