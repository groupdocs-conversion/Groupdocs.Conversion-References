---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för att läsa in presentationsdokument."
type: docs
weight: 2770
url: /sv/net/groupdocs.conversion.options.load/presentationloadoptions/
---
## PresentationLoadOptions class

Alternativ för att läsa in presentationsdokument.

```csharp
public class PresentationLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IMetadataLoadOptions, IResourceLoadingOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PresentationLoadOptions](presentationloadoptions)() | Initierar en ny instans av [`PresentationLoadOptions`](../presentationloadoptions) klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/presentationloadoptions/clearbuiltindocumentproperties) { get; set; } | Tar bort inbyggda metadataegenskaper från dokumentet. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/presentationloadoptions/clearcustomdocumentproperties) { get; set; } | Tar bort anpassade metadataegenskaper från dokumentet. |
| [CommentsPosition](../../groupdocs.conversion.options.load/presentationloadoptions/commentsposition) { get; set; } | Representerar hur kommentarer skrivs ut med bilden. Standard är Ingen. |
| [ConvertOwned](../../groupdocs.conversion.options.load/presentationloadoptions/convertowned) { get; set; } | Implementerar [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned). Standard är false. |
| [ConvertOwner](../../groupdocs.conversion.options.load/presentationloadoptions/convertowner) { get; set; } | Implementerar [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner). Standard är true. |
| [DefaultFont](../../groupdocs.conversion.options.load/presentationloadoptions/defaultfont) { get; set; } | Standardteckensnitt för rendering av presentationen. Följande teckensnitt kommer att användas om ett presentations‑teckensnitt saknas. |
| [Depth](../../groupdocs.conversion.options.load/presentationloadoptions/depth) { get; set; } | Implementerar [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth). Standard: 1. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/presentationloadoptions/fontsubstitutes) { get; set; } | Ersätt specifika teckensnitt vid konvertering av presentationsdokument. |
| [Format](../../groupdocs.conversion.options.load/presentationloadoptions/format) { get; set; } | Inmatningsdokumentets filtyp. Är `null` tills ett format har satts, så testa den för `null` snarare än mot [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), vilket den aldrig är lika med. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Inmatningsdokumentets filtyp. |
| [NotesPosition](../../groupdocs.conversion.options.load/presentationloadoptions/notesposition) { get; set; } | Representerar hur anteckningar skrivs ut med bilden. Standard är Ingen. |
| [Password](../../groupdocs.conversion.options.load/presentationloadoptions/password) { get; set; } | Ange lösenord för att avskydda skyddat dokument. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/presentationloadoptions/preservedocumentstructure) { get; set; } | Bestämmer om dokumentstrukturen ska bevaras vid konvertering till PDF (standard är false). |
| [ShowHiddenSlides](../../groupdocs.conversion.options.load/presentationloadoptions/showhiddenslides) { get; set; } | Visa dolda bilder. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/presentationloadoptions/skipexternalresources) { get; set; } | Implementerar [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [WhitelistedResources](../../groupdocs.conversion.options.load/presentationloadoptions/whitelistedresources) { get; set; } | Implementerar [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |
| [SetVideoConnector](../../groupdocs.conversion.options.load/presentationloadoptions/setvideoconnector)(IPresentationVideoConnector) | Ställ in videodokumentanslutning |

### Se även

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
