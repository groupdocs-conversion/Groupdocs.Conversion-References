---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Opties voor het laden van WordProcessing-documenten."
type: docs
weight: 2950
url: /nl/net/groupdocs.conversion.options.load/wordprocessingloadoptions/
---
## WordProcessingLoadOptions class

Opties voor het laden van WordProcessing-documenten.

```csharp
public class WordProcessingLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageMarginOptions, IPageNumberingLoadOptions, IPageSizeOptions, IResourceLoadingOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [WordProcessingLoadOptions](wordprocessingloadoptions)() | Initialiseert een nieuw exemplaar van de [`WordProcessingLoadOptions`](../wordprocessingloadoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AutoDetectRtlDirection](../../groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection) { get; set; } | Wanneer true (standaard), zullen alinea's en runs waarvan de tekst overwegend van rechts naar links is, hun bidi‑vlaggen laten repareren vóór conversie. Dit komt overeen met de heuristiek die Microsoft Word en LibreOffice toepassen en corrigeert de weergave van Arabische/Hebreeuwse documenten die door generators (met name Google Docs) worden geproduceerd en OOXML uitzenden zonder &lt;w:bidi/&gt; en met &lt;w:rtl w:val=\"0\"/&gt; op runs die alleen RTL‑script bevatten. Stel in op false om de strikte OOXML‑interpretatie van de bron‑markup te behouden. |
| [BookmarkOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/bookmarkoptions) { get; set; } | Bladwijzeropties |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearbuiltindocumentproperties) { get; set; } | Verwijdert ingebouwde metagegevens‑eigenschappen uit het document. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearcustomdocumentproperties) { get; set; } | Verwijdert aangepaste metagegevens‑eigenschappen uit het document. |
| [CommentDisplayMode](../../groupdocs.conversion.options.load/wordprocessingloadoptions/commentdisplaymode) { get; set; } | Specificeert hoe opmerkingen moeten worden weergegeven in het uitvoerdocument. Standaard is ShowInBalloons. |
| [ConvertOwned](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowned) { get; set; } | Implementeert [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Standaard is false |
| [ConvertOwner](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowner) { get; set; } | Implementeert [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Standaard is true |
| [DefaultFont](../../groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont) { get; set; } | Stelt het standaardlettertype in voor een WordProcessing-document. |
| [Depth](../../groupdocs.conversion.options.load/wordprocessingloadoptions/depth) { get; set; } | Implementeert [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Standaard: 1 |
| [EmbedTrueTypeFonts](../../groupdocs.conversion.options.load/wordprocessingloadoptions/embedtruetypefonts) { get; set; } | Als EmbedTrueTypeFonts true is, embedt GroupDocs.Conversion TrueType-lettertypen in het uitvoerdocument. Standaard: true |
| [FontConfigSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontconfigsubstitutionenabled) { get; set; } | Vervangt automatisch ontbrekende lettertypen op basis van FontConfig in het systeem. Standaard: false. |
| [FontInfoSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontinfosubstitutionenabled) { get; set; } | Vervangt automatisch ontbrekende lettertypen op basis van FontInfo in het document. Standaard: false. |
| [FontNameSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontnamesubstitutionenabled) { get; set; } | Vervangt automatisch ontbrekende lettertypen op basis van de lettertype‑naam. Standaard: false. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes) { get; set; } | Vervangt specifieke lettertypen bij het converteren van een WordsProcessing-document. |
| [FontTransformations](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fonttransformations) { get; set; } | Transformeer bestaande lettertypen nadat het document is geladen en de lettertypevervanging voltooid is. Lettertype‑transformaties kunnen alle lettertypen in het document wijzigen, inclusief lettertypen die succesvol geladen zijn. |
| [Format](../../groupdocs.conversion.options.load/wordprocessingloadoptions/format) { get; set; } | Invoerdocument bestandstype. Is `null` totdat een formaat is ingesteld, dus test op `null` in plaats van tegen [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), waaraan het nooit gelijk is. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Invoerdocument bestandstype. |
| [HideWordTrackedChanges](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hidewordtrackedchanges) { get; set; } | Verberg markup en volg wijzigingen voor Word-documenten. |
| [HyphenationOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenationoptions) { get; set; } | Stel afbreekopties in voor WordProcessing-documenten. |
| [KeepDateFieldOriginalValue](../../groupdocs.conversion.options.load/wordprocessingloadoptions/keepdatefieldoriginalvalue) { get; set; } | Behoud de oorspronkelijke waarde van het datumveld. Standaard: false |
| [MarginSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/marginsettings) { get; set; } | Instellingen voor paginamarges |
| [PageNumbering](../../groupdocs.conversion.options.load/wordprocessingloadoptions/pagenumbering) { get; set; } | Schakel het genereren van paginanummering in het geconverteerde document in of uit. Standaard: false |
| [Password](../../groupdocs.conversion.options.load/wordprocessingloadoptions/password) { get; set; } | Stel wachtwoord in om een beschermd document te ontgrendelen. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preservedocumentstructure) { get; set; } | Bepaalt of de documentstructuur behouden moet blijven bij het converteren naar PDF (standaard is false). |
| [PreserveFormFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preserveformfields) { get; set; } | Specificeert of Microsoft Word-formuliervelden behouden moeten blijven als formuliervelden in PDF of moeten worden geconverteerd naar tekst. Standaard is false. |
| [ShowFullCommenterName](../../groupdocs.conversion.options.load/wordprocessingloadoptions/showfullcommentername) { get; set; } | Toon de volledige naam van de commentator in opmerkingen. Standaard is false. |
| [SizeSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/sizesettings) { get; set; } | Instellingen voor paginagrootte |
| [SkipExternalResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/skipexternalresources) { get; set; } | Implementeert [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UpdateFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatefields) { get; set; } | Werk velden bij na het laden. Standaard: false |
| [UpdatePageLayout](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatepagelayout) { get; set; } | Werk paginalay-out bij na het laden. Standaard: false |
| [UseTextShaper](../../groupdocs.conversion.options.load/wordprocessingloadoptions/usetextshaper) { get; set; } | Specificeert of een tekst‑shaper moet worden gebruikt voor een betere kerning-weergave. Standaard is false. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/whitelistedresources) { get; set; } | Implementeert [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Opmerkingen

**Font Processing Pipeline:**

**Phase 1 - Font Substitution (during document loading):**

• Verwerkt ontbrekende/onbeschikbare lettertypen met behulp van FontSubstitutes, DefaultFont en systeemvervanging

• Verwerkingsvolgorde: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

**Phase 2 - Font Replacement (after document loading):**

• Wijzigt eventuele bestaande lettertypen in het geladen document met behulp van FontReplacements

• Toegepast nadat alle lettertypevervanging voltooid is

### Zie ook

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

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
