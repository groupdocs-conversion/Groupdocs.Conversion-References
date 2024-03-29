---
title: WordProcessingLoadOptions
second_title: GroupDocs.Conversion for .NET API Referens
description: Alternativ för att ladda WordProcessingdokument.
type: docs
weight: 2360
url: /sv/net/groupdocs.conversion.options.load/wordprocessingloadoptions/
---
## WordProcessingLoadOptions class

Alternativ för att ladda WordProcessing-dokument.

```csharp
public class WordProcessingLoadOptions : LoadOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [WordProcessingLoadOptions](wordprocessingloadoptions)() | Initierar ny instans av[`WordProcessingLoadOptions`](../wordprocessingloadoptions) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AutoFontSubstitution](../../groupdocs.conversion.options.load/wordprocessingloadoptions/autofontsubstitution) { get; set; } | Om AutoFontSubstitution är inaktiverat, använder GroupDocs.Conversion DefaultFont för att ersätta saknade teckensnitt. Om AutoFontSubstitution är aktiverat, utvärderar GroupDocs.Conversion alla relaterade fält i FontInfo (Panose, Sig etc) för det saknade teckensnittet och hittar närmast matchning bland de tillgängliga teckensnittskällorna. Observera att teckensnittsersättningsmekanismen kommer att åsidosätta DefaultFont i fall då FontInfo för det saknade teckensnittet finns i dokumentet. Standardvärdet är True. |
| [BookmarkOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/bookmarkoptions) { get; set; } | Bokmärkesalternativ |
| [DefaultFont](../../groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont) { get; set; } | Standardteckensnitt för Words-dokument. Följande teckensnitt kommer att användas om ett teckensnitt saknas. |
| [EmbedTrueTypeFonts](../../groupdocs.conversion.options.load/wordprocessingloadoptions/embedtruetypefonts) { get; set; } | Om EmbedTrueTypeFonts är sant, bäddar GroupDocs.Conversion in true type-teckensnitt i utdatadokumentet. Standard: false |
| [FontSubstitutes](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes) { get; set; } | Ersätt specifika teckensnitt när du konverterar Words-dokument. |
| [Format](../../groupdocs.conversion.options.load/wordprocessingloadoptions/format) { get; set; } | Inmatningsdokumentfiltyp. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Inmatningsdokumentfiltyp. |
| [HideComments](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hidecomments) { get; set; } | Dölj kommentarer. |
| [HideWordTrackedChanges](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hidewordtrackedchanges) { get; set; } | Dölj markeringar och spåra ändringar för Word-dokument. |
| [KeepDateFieldOriginalValue](../../groupdocs.conversion.options.load/wordprocessingloadoptions/keepdatefieldoriginalvalue) { get; set; } | Behåll datumfältets ursprungliga värde. Standard: false |
| [Password](../../groupdocs.conversion.options.load/wordprocessingloadoptions/password) { get; set; } | Ange lösenord för att avskydda skyddat dokument. |
| [PreserveFormFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preserveformfields) { get; set; } | Anger om Microsoft Word-formulärfält ska bevaras som formulärfält i PDF eller konvertera dem till text. Standard är false. |
| [UpdateFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatefields) { get; set; } | Uppdatera fält efter laddning. Standard: false |
| [UpdatePageLayout](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatepagelayout) { get; set; } | Uppdatera sidlayouten efter laddning. Standard: false |
| [UseTextShaper](../../groupdocs.conversion.options.load/wordprocessingloadoptions/usetextshaper) { get; set; } | Anger om en textformare ska användas för bättre kerningvisning. Standard är false. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standard hash-funktion. |

### Se även

* class [LoadOptions](../loadoptions)
* namnutrymme [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* hopsättning [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
