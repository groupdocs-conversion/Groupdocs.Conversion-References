---
title: "EmailLoadOptions"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Alternativ för att läsa in e‑postdokument."
type: docs
weight: 2500
url: /sv/net/groupdocs.conversion.options.load/emailloadoptions/
---
## EmailLoadOptions class

Alternativ för att läsa in e‑postdokument.

```csharp
public sealed class EmailLoadOptions : LoadOptions, ICustomCssStyleOptions, 
    IDocumentsContainerLoadOptions, IFontSubstituteLoadOptions, IPageLayoutOptions, 
    IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, IResourceLoadingOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [EmailLoadOptions](emailloadoptions)() | Initierar en ny instans av [`EmailLoadOptions`](../emailloadoptions) klass. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/attachmenticons) { get; set; } | Hämtar eller anger listan med bilagikon. Listan kan anpassas för att tillhandahålla specifika ikoner för olika filtyper. Som standard innehåller den vanliga filtypsikoner. |
| [ConvertOwned](../../groupdocs.conversion.options.load/emailloadoptions/convertowned) { get; set; } | Implementerar [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Standardvärdet är true |
| [ConvertOwner](../../groupdocs.conversion.options.load/emailloadoptions/convertowner) { get; set; } | Implementerar [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner). Standard är true. |
| [CustomCssStyle](../../groupdocs.conversion.options.load/emailloadoptions/customcssstyle) { get; set; } | Implementerar [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [DefaultFont](../../groupdocs.conversion.options.load/emailloadoptions/defaultfont) { get; set; } | Standardteckensnitt för e‑postdokument. Följande teckensnitt kommer att användas om ett teckensnitt saknas. |
| [Depth](../../groupdocs.conversion.options.load/emailloadoptions/depth) { get; set; } | Implementerar [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth). Standard: 1. |
| [DisplayAttachments](../../groupdocs.conversion.options.load/emailloadoptions/displayattachments) { get; set; } | Alternativ för att visa eller dölja bilagor i rubriken. Standard: true. |
| [DisplayBccEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaybccemailaddress) { get; set; } | Alternativ för att visa eller dölja \"Bcc\"‑e‑postadress. Standard: false. |
| [DisplayCcEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayccemailaddress) { get; set; } | Alternativ för att visa eller dölja \"Cc\"‑e‑postadress. Standard: false. |
| [DisplayEmailAddresses](../../groupdocs.conversion.options.load/emailloadoptions/displayemailaddresses) { get; set; } | Alternativ för att styra om e‑postadresser visas bredvid namn. Exempel: \"John Doe &lt;john.doe@sample.com&gt;\" eller bara \"John Doe.\" Standard: true. |
| [DisplayFromEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayfromemailaddress) { get; set; } | Alternativ för att visa eller dölja \"from\"‑e‑postadress. Standard: true. |
| [DisplayHeader](../../groupdocs.conversion.options.load/emailloadoptions/displayheader) { get; set; } | Alternativ för att visa eller dölja e‑postrubriken. Standard: true. |
| [DisplaySent](../../groupdocs.conversion.options.load/emailloadoptions/displaysent) { get; set; } | Alternativ för att visa eller dölja skickat datum/tid i rubriken. Standard: true. |
| [DisplaySubject](../../groupdocs.conversion.options.load/emailloadoptions/displaysubject) { get; set; } | Alternativ för att visa eller dölja ämnet i rubriken. Standard: true. |
| [DisplayToEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaytoemailaddress) { get; set; } | Alternativ för att visa eller dölja \"to\"‑e‑postadress. Standard: true. |
| [FieldTextMap](../../groupdocs.conversion.options.load/emailloadoptions/fieldtextmap) { get; set; } | Mappningen mellan e‑postmeddelande [`EmailField`](../emailfield) och fältets textrepresentation |
| [FontSubstitutes](../../groupdocs.conversion.options.load/emailloadoptions/fontsubstitutes) { get; set; } | Lista med teckensnittsersättningar. |
| [Format](../../groupdocs.conversion.options.load/emailloadoptions/format) { get; set; } | Inmatningsdokumentets filtyp. Är `null` tills ett format har satts, så testa den för `null` snarare än mot [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), vilket den aldrig är lika med. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Inmatningsdokumentets filtyp. |
| [MarginSettings](../../groupdocs.conversion.options.load/emailloadoptions/marginsettings) { get; set; } | Inställningar för sidmarginaler |
| [OrientationSettings](../../groupdocs.conversion.options.load/emailloadoptions/orientationsettings) { get; set; } | Inställningar för sidorientering |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/emailloadoptions/pagelayoutoptions) { get; set; } | Implementerar [`PageLayoutOptions`](../ipagelayoutoptions/pagelayoutoptions) |
| [PreserveOriginalDate](../../groupdocs.conversion.options.load/emailloadoptions/preserveoriginaldate) { get; set; } | Definierar om det behövs behålla den ursprungliga datumrubriksträngen i e‑postmeddelandet vid sparande eller inte (Standardvärdet är true) |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/emailloadoptions/resourceloadingtimeout) { get; set; } | Timeout för inläsning av externa resurser |
| [SizeSettings](../../groupdocs.conversion.options.load/emailloadoptions/sizesettings) { get; set; } | Inställningar för sidstorlek |
| [SkipExternalResources](../../groupdocs.conversion.options.load/emailloadoptions/skipexternalresources) { get; set; } | Implementerar [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [TimeZoneOffset](../../groupdocs.conversion.options.load/emailloadoptions/timezoneoffset) { get; set; } | Hämtar eller anger förskjutningen i Coordinated Universal Time (UTC) för meddelandedatumen. Denna egenskap definierar tidszonskillnaden mellan lokal tid och UTC. |
| [UseDefaultAttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/usedefaultattachmenticons) { get; set; } | Hämtar eller anger om standardbilagikon ska användas. Standard: true. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/emailloadoptions/whitelistedresources) { get; set; } | Implementerar [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/emailloadoptions/clone)() | Klonar aktuell instans. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestämmer om två objektinstanser är lika. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestämmer om två objektinstanser är lika. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Fungerar som standardhash-funktion. |

### Se även

* class [LoadOptions](../loadoptions)
* interface [ICustomCssStyleOptions](../icustomcssstyleoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IPageLayoutOptions](../ipagelayoutoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
