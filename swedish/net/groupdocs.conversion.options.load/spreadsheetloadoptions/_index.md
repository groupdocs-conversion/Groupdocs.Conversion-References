---
title: SpreadsheetLoadOptions
second_title: GroupDocs.Conversion for .NET API Referens
description: Alternativ för att ladda kalkylarksdokument.
type: docs
weight: 2010
url: /sv/net/groupdocs.conversion.options.load/spreadsheetloadoptions/
---
## SpreadsheetLoadOptions class

Alternativ för att ladda kalkylarksdokument.

```csharp
public class SpreadsheetLoadOptions : LoadOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | Initierar ny instans av[`SpreadsheetLoadOptions`](../spreadsheetloadoptions) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | Om kontrollera begränsning av excel-fil när användaren ändrar cellrelaterade objekt. Till exempel tillåter excel inte inmatning av strängvärden som är längre än 32K. När du anger ett värde som är längre än 32K, om den här egenskapen är sann, får du ett undantag. Om den här egenskapen är falsk kommer vi att acceptera ditt inmatade strängvärde som cellens värde så att du senare kan mata ut hela strängvärdet för andra filformat som CSV. Men om du har angett en sådan typ av värde som är ogiltigt för Excel-filformat, bör du inte spara arbetsboken som Excel-filformat senare. Annars kan det uppstå ett oväntat fel för den genererade excel-filen. |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Konvertera specifikt intervall vid konvertering till annat än kalkylarksformat. Exempel: "D1:F8". |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | Hämta eller ställ in systemkulturinformationen när filen laddas |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | Standardteckensnitt för kalkylarksdokument. Följande teckensnitt kommer att användas om ett teckensnitt saknas. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | Ersätt specifika teckensnitt vid konvertering av kalkylarksdokument. |
| [Format](../../groupdocs.conversion.options.load/spreadsheetloadoptions/format) { get; set; } | Inmatningsdokumentfiltyp. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Inmatningsdokumentfiltyp. |
| [HideComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/hidecomments) { get; set; } | Dölj kommentarer. |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | Om OnePagePerSheet är sant kommer innehållet i arket att konverteras till en sida i PDF-dokumentet. Standardvärdet är sant. |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | Om True och konverterar till PDF är konverteringen optimerad för bättre filstorlek än utskriftskvalitet. |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | Ange lösenord för att avskydda skyddat dokument. |
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

* class [LoadOptions](../loadoptions)
* namnutrymme [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* hopsättning [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->