---
title: CsvLoadOptions
second_title: GroupDocs.Conversion for .NET API Referens
description: Alternativ för att ladda Csvdokument.
type: docs
weight: 1860
url: /sv/net/groupdocs.conversion.options.load/csvloadoptions/
---
## CsvLoadOptions class

Alternativ för att ladda Csv-dokument.

```csharp
public sealed class CsvLoadOptions : SpreadsheetLoadOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [CsvLoadOptions](csvloadoptions)() | Initierar ny instans av[`CsvLoadOptions`](../csvloadoptions) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Om kontrollera begränsning av excel-fil när användaren ändrar cellrelaterade objekt. Till exempel tillåter excel inte inmatning av strängvärden som är längre än 32K. När du anger ett värde som är längre än 32K, om den här egenskapen är sann, får du ett undantag. Om den här egenskapen är falsk kommer vi att acceptera ditt inmatade strängvärde som cellens värde så att du senare kan mata ut hela strängvärdet för andra filformat som CSV. Men om du har angett en sådan typ av värde som är ogiltigt för Excel-filformat, bör du inte spara arbetsboken som Excel-filformat senare. Annars kan det uppstå ett oväntat fel för den genererade excel-filen. |
| [ConvertDateTimeData](../../groupdocs.conversion.options.load/csvloadoptions/convertdatetimedata) { get; set; } | Indikerar om strängen i filen är konverterad till datum. Standard är True. |
| [ConvertNumericData](../../groupdocs.conversion.options.load/csvloadoptions/convertnumericdata) { get; set; } | Indikerar om strängen i filen är konverterad till numerisk. Standard är True. |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Konvertera specifikt intervall vid konvertering till annat än kalkylarksformat. Exempel: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Hämta eller ställ in systemkulturinformationen när filen laddas |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Standardteckensnitt för kalkylarksdokument. Följande teckensnitt kommer att användas om ett teckensnitt saknas. |
| [Encoding](../../groupdocs.conversion.options.load/csvloadoptions/encoding) { get; set; } | Kodning. Standard är Encoding.Default. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Ersätt specifika teckensnitt vid konvertering av kalkylarksdokument. |
| [Format](../../groupdocs.conversion.options.load/spreadsheetloadoptions/format) { get; set; } | Inmatningsdokumentfiltyp. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Inmatningsdokumentfiltyp. |
| [HasFormula](../../groupdocs.conversion.options.load/csvloadoptions/hasformula) { get; set; } | Anger om text är formel om den börjar med "=". |
| [HideComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/hidecomments) { get; set; } | Dölj kommentarer. |
| [IsMultiEncoded](../../groupdocs.conversion.options.load/csvloadoptions/ismultiencoded) { get; set; } | True betyder att filen innehåller flera kodningar. |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | Om OnePagePerSheet är sant kommer innehållet i arket att konverteras till en sida i PDF-dokumentet. Standardvärdet är sant. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | Om True och konverterar till PDF är konverteringen optimerad för bättre filstorlek än utskriftskvalitet. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Ange lösenord för att avskydda skyddat dokument. |
| [Separator](../../groupdocs.conversion.options.load/csvloadoptions/separator) { get; set; } | Avgränsare för en Csv-fil. |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | Bladnamn att konvertera |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | Visa rutnätslinjer vid konvertering av Excel-filer. |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | Visa dolda ark när du konverterar Excel-filer. |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | Hoppa över tomma rader och kolumner vid konvertering. Standard är True. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | Klonar aktuell instans. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standard hash-funktion. |

### Se även

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* namnutrymme [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* hopsättning [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
