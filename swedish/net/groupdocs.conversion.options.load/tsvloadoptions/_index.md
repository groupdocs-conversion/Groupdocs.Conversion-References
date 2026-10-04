---
title: "TsvLoadOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för att läsa in Tsv-dokument."
type: docs
weight: 2850
url: /sv/net/groupdocs.conversion.options.load/tsvloadoptions/
---
## TsvLoadOptions class

Alternativ för att läsa in Tsv-dokument.

```csharp
public sealed class TsvLoadOptions : SpreadsheetLoadOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [TsvLoadOptions](tsvloadoptions)() | Initierar en ny instans av klassen [`TsvLoadOptions`](../tsvloadoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AllColumnsInOnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/allcolumnsinonepagepersheet) { get; set; } | Om AllColumnsInOnePagePerSheet är true, kommer allt kolumninnehåll på ett blad att skrivas ut på endast en sida i resultatet. Bredden på pappersstorleken i pagesetup blir ogiltig, men de övriga inställningarna i pagesetup tillämpas fortfarande. |
| [AutoFitRows](../../groupdocs.conversion.options.load/spreadsheetloadoptions/autofitrows) { get; set; } | Anpassar automatiskt alla rader vid konvertering |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Anger om restriktioner för Excel‑filen ska kontrolleras när användaren ändrar cellrelaterade objekt. Till exempel tillåter Excel inte att en strängvärde längre än 32 K matas in. När du anger ett värde som är längre än 32 K, får du ett Exception om den här egenskapen är true. Om egenskapen är false accepterar vi ditt inmatade strängvärde som cellens värde så att du senare kan skriva ut hela strängvärdet för andra filformat såsom CSV. Däremot, om du har angett ett värde som är ogiltigt för Excel‑filformatet bör du inte spara arbetsboken som Excel‑filformat senare. Annars kan det uppstå oväntade fel i den genererade Excel‑filen. |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearbuiltindocumentproperties) { get; set; } | Tar bort inbyggda metadataegenskaper från dokumentet. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearcustomdocumentproperties) { get; set; } | Tar bort anpassade metadataegenskaper från dokumentet. |
| [ColumnsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/columnsperpage) { get; set; } | Dela ett arbetsblad i sidor efter kolumner. Standardvärdet är 0, ingen paginering. |
| [ConvertOwned](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowned) { get; set; } | Implementerar [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned). Standard är false. |
| [ConvertOwner](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowner) { get; set; } | Implementerar [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner). Standard är true. |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Konvertera ett specifikt område när du konverterar till annat än kalkylbladsformat. Exempel: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Hämtar eller anger systemets kulturinformation när filen laddas |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Standardteckensnitt för kalkylbladsdokument. Följande teckensnitt kommer att användas om ett teckensnitt saknas. |
| [Depth](../../groupdocs.conversion.options.load/spreadsheetloadoptions/depth) { get; set; } | Implementerar [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth). Standard: 1. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Ersätt specifika teckensnitt vid konvertering av kalkylbladsdokument. |
| [Format](../../groupdocs.conversion.options.load/tsvloadoptions/format) { get; } | Inmatningsdokumentets filtyp. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Inmatningsdokumentets filtyp. |
| [IgnoreFormulaCalculationErrors](../../groupdocs.conversion.options.load/spreadsheetloadoptions/ignoreformulacalculationerrors) { get; set; } | Anger om formelberäkningsfel ska ignoreras. Felet kan vara en funktion som inte stöds, externa länkar osv. Standardvärdet är false. |
| [MarginSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/marginsettings) { get; set; } | Inställningar för sidmarginaler |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | Om OnePagePerSheet är true konverteras bladets innehåll till en sida i PDF‑dokumentet. Standardvärdet är true. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | Om True och konvertering till Pdf optimeras konverteringen för en bättre filstorlek än utskriftskvalitet. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Ange lösenord för att avskydda skyddat dokument. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/spreadsheetloadoptions/preservedocumentstructure) { get; set; } | Bestämmer om dokumentstrukturen ska bevaras vid konvertering till PDF (standard är false). |
| [PrintComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/printcomments) { get; set; } | Representerar hur kommentarer skrivs ut med bladet. Standardvärdet är PrintNoComments. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/resetfontfolders) { get; set; } | Återställ teckensnittsmappar innan dokumentet laddas |
| [RowsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/rowsperpage) { get; set; } | Dela ett arbetsblad i sidor efter rader. Standardvärdet är 0, ingen paginering. |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | Lista över bladindex att konvertera. Indexen måste vara nollbaserade |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | Bladnamn att konvertera |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Visa rutnät när Excel‑filer konverteras. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Visa dolda blad när Excel‑filer konverteras. |
| [SizeSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sizesettings) { get; set; } | Inställningar för sidstorlek |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | Hoppar över tomma rader och kolumner vid konvertering. Standardvärdet är True. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipexternalresources) { get; set; } | Implementerar [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [SkipFooters](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipfooters) { get; set; } | Hoppa över sidfötter vid konvertering av kalkylbladsdokument. Standard: false. |
| [SkipHeaders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipheaders) { get; set; } | Hoppa över rubriker när du konverterar kalkylbladsdokument. Standard: false. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/whitelistedresources) { get; set; } | Implementerar [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | Klonar aktuell instans. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
