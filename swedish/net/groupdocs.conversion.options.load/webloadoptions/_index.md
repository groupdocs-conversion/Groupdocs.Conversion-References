---
title: "WebLoadOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för att läsa in webbdokument."
type: docs
weight: 2920
url: /sv/net/groupdocs.conversion.options.load/webloadoptions/
---
## WebLoadOptions class

Alternativ för att läsa in webbdokument.

```csharp
public class WebLoadOptions : LoadOptions, ICustomCssStyleOptions, IPageLayoutOptions, 
    IPageMarginOptions, IPageNumberingLoadOptions, IPageOrientationOptions, IPageSizeOptions, 
    IResourceLoadingOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [WebLoadOptions](webloadoptions)() | Initierar en ny instans av klassen [`WebLoadOptions`](../webloadoptions). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BasePath](../../groupdocs.conversion.options.load/webloadoptions/basepath) { get; set; } | Basvägen/URL för HTML |
| [ConfigureHeaders](../../groupdocs.conversion.options.load/webloadoptions/configureheaders) { get; set; } | Åtgärd för konfiguration av begärans rubriker. Första parametern för åtgärden är Uri. |
| [CredentialsProvider](../../groupdocs.conversion.options.load/webloadoptions/credentialsprovider) { get; set; } | Leverantör av autentiseringsuppgifter för Uri. |
| [CustomCssStyle](../../groupdocs.conversion.options.load/webloadoptions/customcssstyle) { get; set; } | Implementerar [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [Encoding](../../groupdocs.conversion.options.load/webloadoptions/encoding) { get; set; } | Hämtar eller anger kodningen som ska användas när webb dokumentet laddas. Om egenskapen är null kommer kodningen att bestämmas från dokumentets teckenuppsättningsattribut. |
| [Format](../../groupdocs.conversion.options.load/webloadoptions/format) { get; set; } | Inmatningsdokumentets filtyp. Är `null` tills ett format har satts, så testa den för `null` snarare än mot [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), vilket den aldrig är lika med. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Inmatningsdokumentets filtyp. |
| [HtmlRenderingMode](../../groupdocs.conversion.options.load/webloadoptions/htmlrenderingmode) { get; set; } | Styr hur HTML-innehåll renderas. Standard: AbsolutePositioning |
| [MarginSettings](../../groupdocs.conversion.options.load/webloadoptions/marginsettings) { get; set; } | Inställningar för sidmarginaler |
| [OrientationSettings](../../groupdocs.conversion.options.load/webloadoptions/orientationsettings) { get; set; } | Inställningar för sidorientering |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/webloadoptions/pagelayoutoptions) { get; set; } | Anger sidlayoutalternativen när webbdokument laddas. |
| [PageNumbering](../../groupdocs.conversion.options.load/webloadoptions/pagenumbering) { get; set; } | Aktivera eller inaktivera generering av sidnumrering i konverterat dokument. Standard: false. |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/webloadoptions/resourceloadingtimeout) { get; set; } | Timeout för inläsning av externa resurser |
| [SizeSettings](../../groupdocs.conversion.options.load/webloadoptions/sizesettings) { get; set; } | Inställningar för sidstorlek |
| [SkipExternalResources](../../groupdocs.conversion.options.load/webloadoptions/skipexternalresources) { get; set; } | Implementerar [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UsePdf](../../groupdocs.conversion.options.load/webloadoptions/usepdf) { get; set; } | Använd pdf för konverteringen. Standard: false |
| [WhitelistedResources](../../groupdocs.conversion.options.load/webloadoptions/whitelistedresources) { get; set; } | Implementerar [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |
| [Zoom](../../groupdocs.conversion.options.load/webloadoptions/zoom) { get; set; } | Anger zoomnivån som en procentsats. Zoomnivån tillämpas på dokumentets &lt;body&gt;-tagg före konvertering och skalar dokumentets visuella utseende. Ett värde på 100% motsvarar originalstorleken. Standardvärdet är 100. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [LoadOptions](../loadoptions)
* interface [ICustomCssStyleOptions](../icustomcssstyleoptions)
* interface [IPageLayoutOptions](../ipagelayoutoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
