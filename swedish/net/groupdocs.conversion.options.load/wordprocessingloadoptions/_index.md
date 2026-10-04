---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för att läsa in WordProcessing-dokument."
type: docs
weight: 2950
url: /sv/net/groupdocs.conversion.options.load/wordprocessingloadoptions/
---
## WordProcessingLoadOptions class

Alternativ för att läsa in WordProcessing-dokument.

```csharp
public class WordProcessingLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageMarginOptions, IPageNumberingLoadOptions, IPageSizeOptions, IResourceLoadingOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [WordProcessingLoadOptions](wordprocessingloadoptions)() | Initierar en ny instans av klassen [`WordProcessingLoadOptions`](../wordprocessingloadoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AutoDetectRtlDirection](../../groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection) { get; set; } | När true (standard) repareras bidi-flaggor för stycken och körningar vars text huvudsakligen är från höger till vänster innan konvertering. Detta motsvarar den heuristik som Microsoft Word och LibreOffice använder och åtgärdar rendering av arabiska/hebreiska dokument som genereras av verktyg (särskilt Google Docs) som skapar OOXML utan &lt;w:bidi/&gt; och med &lt;w:rtl w:val="0"/&gt; på körningar som endast innehåller RTL-skript. Ställ in på false för att bevara strikt OOXML‑tolkning av källmarkupen. |
| [BookmarkOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/bookmarkoptions) { get; set; } | Bokmärkesalternativ |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearbuiltindocumentproperties) { get; set; } | Tar bort inbyggda metadataegenskaper från dokumentet. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearcustomdocumentproperties) { get; set; } | Tar bort anpassade metadataegenskaper från dokumentet. |
| [CommentDisplayMode](../../groupdocs.conversion.options.load/wordprocessingloadoptions/commentdisplaymode) { get; set; } | Anger hur kommentarer ska visas i utdata‑dokumentet. Standard är ShowInBalloons. |
| [ConvertOwned](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowned) { get; set; } | Implementerar [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned). Standard är false. |
| [ConvertOwner](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowner) { get; set; } | Implementerar [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner). Standard är true. |
| [DefaultFont](../../groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont) { get; set; } | Ställer in standardteckensnittet för ett WordProcessing‑dokument. |
| [Depth](../../groupdocs.conversion.options.load/wordprocessingloadoptions/depth) { get; set; } | Implementerar [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth). Standard: 1. |
| [EmbedTrueTypeFonts](../../groupdocs.conversion.options.load/wordprocessingloadoptions/embedtruetypefonts) { get; set; } | Om EmbedTrueTypeFonts är true, bäddar GroupDocs.Conversion in TrueType‑teckensnitt i utdata‑dokumentet. Standard: true. |
| [FontConfigSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontconfigsubstitutionenabled) { get; set; } | Ersätter automatiskt saknade teckensnitt baserat på FontConfig i systemet. Standard: false. |
| [FontInfoSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontinfosubstitutionenabled) { get; set; } | Ersätter automatiskt saknade teckensnitt baserat på FontInfo i dokumentet. Standard: false. |
| [FontNameSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontnamesubstitutionenabled) { get; set; } | Ersätter automatiskt saknade teckensnitt baserat på teckensnittsnamnet. Standard: false. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes) { get; set; } | Ersätter specifika teckensnitt vid konvertering av ett WordsProcessing‑dokument. |
| [FontTransformations](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fonttransformations) { get; set; } | Transformera befintliga teckensnitt efter att dokumentet har laddats och teckensnittsersättning är klar. Teckensnittstransformationer kan ändra alla teckensnitt i dokumentet, inklusive teckensnitt som laddades framgångsrikt. |
| [Format](../../groupdocs.conversion.options.load/wordprocessingloadoptions/format) { get; set; } | Inmatningsdokumentets filtyp. Är `null` tills ett format har satts, så testa den för `null` snarare än mot [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), vilket den aldrig är lika med. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Inmatningsdokumentets filtyp. |
| [HideWordTrackedChanges](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hidewordtrackedchanges) { get; set; } | Dölj markup och spåra ändringar för Word‑dokument. |
| [HyphenationOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenationoptions) { get; set; } | Ställ in avstavningsalternativ för WordProcessing‑dokument. |
| [KeepDateFieldOriginalValue](../../groupdocs.conversion.options.load/wordprocessingloadoptions/keepdatefieldoriginalvalue) { get; set; } | Behåll det ursprungliga värdet för datumfältet. Standard: false. |
| [MarginSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/marginsettings) { get; set; } | Inställningar för sidmarginaler |
| [PageNumbering](../../groupdocs.conversion.options.load/wordprocessingloadoptions/pagenumbering) { get; set; } | Aktivera eller inaktivera generering av sidnumrering i konverterat dokument. Standard: false. |
| [Password](../../groupdocs.conversion.options.load/wordprocessingloadoptions/password) { get; set; } | Ange lösenord för att avskydda skyddat dokument. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preservedocumentstructure) { get; set; } | Bestämmer om dokumentstrukturen ska bevaras vid konvertering till PDF (standard är false). |
| [PreserveFormFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preserveformfields) { get; set; } | Anger om Microsoft Word‑formulärfält ska bevaras som formulärfält i PDF eller konverteras till text. Standard är false. |
| [ShowFullCommenterName](../../groupdocs.conversion.options.load/wordprocessingloadoptions/showfullcommentername) { get; set; } | Visa fullständigt kommentatorsnamn i kommentarer. Standard är false. |
| [SizeSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/sizesettings) { get; set; } | Inställningar för sidstorlek |
| [SkipExternalResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/skipexternalresources) { get; set; } | Implementerar [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UpdateFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatefields) { get; set; } | Uppdatera fält efter inläsning. Standard: false |
| [UpdatePageLayout](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatepagelayout) { get; set; } | Uppdatera sidlayout efter inläsning. Standard: false |
| [UseTextShaper](../../groupdocs.conversion.options.load/wordprocessingloadoptions/usetextshaper) { get; set; } | Anger om en textformare ska användas för bättre kerningvisning. Standard är false. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/whitelistedresources) { get; set; } | Implementerar [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Anmärkningar

**Font Processing Pipeline:**

**Phase 1 - Font Substitution (during document loading):**

• Hanterar saknade/otillgängliga teckensnitt med FontSubstitutes, DefaultFont och systemersättning

• Bearbetningsordning: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

**Phase 2 - Font Replacement (after document loading):**

• Modifierar befintliga teckensnitt i det inlästa dokumentet med FontReplacements

• Tillämpas efter att all teckensnittsersättning är klar

### Se även

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
