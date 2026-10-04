---
title: "EmailLoadOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Opties voor het laden van e‑maildocumenten."
type: docs
weight: 2500
url: /nl/net/groupdocs.conversion.options.load/emailloadoptions/
---
## EmailLoadOptions class

Opties voor het laden van e‑maildocumenten.

```csharp
public sealed class EmailLoadOptions : LoadOptions, ICustomCssStyleOptions, 
    IDocumentsContainerLoadOptions, IFontSubstituteLoadOptions, IPageLayoutOptions, 
    IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, IResourceLoadingOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [EmailLoadOptions](emailloadoptions)() | Initialiseert een nieuw exemplaar van de [`EmailLoadOptions`](../emailloadoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/attachmenticons) { get; set; } | Haalt de lijst met bijlage‑pictogrammen op of stelt deze in. De lijst kan worden aangepast om specifieke pictogrammen voor verschillende bestandstypen te bieden. Standaard bevat deze veelvoorkomende bestandstype‑pictogrammen. |
| [ConvertOwned](../../groupdocs.conversion.options.load/emailloadoptions/convertowned) { get; set; } | Implementeert [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Standaard is true |
| [ConvertOwner](../../groupdocs.conversion.options.load/emailloadoptions/convertowner) { get; set; } | Implementeert [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Standaard is true |
| [CustomCssStyle](../../groupdocs.conversion.options.load/emailloadoptions/customcssstyle) { get; set; } | Implementeert [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [DefaultFont](../../groupdocs.conversion.options.load/emailloadoptions/defaultfont) { get; set; } | Standaardlettertype voor e-maildocument. Het volgende lettertype wordt gebruikt als een lettertype ontbreekt. |
| [Depth](../../groupdocs.conversion.options.load/emailloadoptions/depth) { get; set; } | Implementeert [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Standaard: 1 |
| [DisplayAttachments](../../groupdocs.conversion.options.load/emailloadoptions/displayattachments) { get; set; } | Optie om bijlagen in de header weer te geven of te verbergen. Standaard: true. |
| [DisplayBccEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaybccemailaddress) { get; set; } | Optie om het "Bcc" e-mailadres weer te geven of te verbergen. Standaard: false. |
| [DisplayCcEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayccemailaddress) { get; set; } | Optie om het "Cc" e-mailadres weer te geven of te verbergen. Standaard: false. |
| [DisplayEmailAddresses](../../groupdocs.conversion.options.load/emailloadoptions/displayemailaddresses) { get; set; } | Optie om te bepalen of e-mailadressen naast namen worden weergegeven. Voorbeeld: "John Doe &lt;john.doe@sample.com&gt;" of alleen "John Doe." Standaard: true. |
| [DisplayFromEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayfromemailaddress) { get; set; } | Optie om het "from" e-mailadres weer te geven of te verbergen. Standaard: true. |
| [DisplayHeader](../../groupdocs.conversion.options.load/emailloadoptions/displayheader) { get; set; } | Optie om de e-mailheader weer te geven of te verbergen. Standaard: true. |
| [DisplaySent](../../groupdocs.conversion.options.load/emailloadoptions/displaysent) { get; set; } | Optie om verzenddatum/tijd in de header weer te geven of te verbergen. Standaard: true. |
| [DisplaySubject](../../groupdocs.conversion.options.load/emailloadoptions/displaysubject) { get; set; } | Optie om het onderwerp in de header weer te geven of te verbergen. Standaard: true. |
| [DisplayToEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaytoemailaddress) { get; set; } | Optie om het "to" e-mailadres weer te geven of te verbergen. Standaard: true. |
| [FieldTextMap](../../groupdocs.conversion.options.load/emailloadoptions/fieldtextmap) { get; set; } | De mapping tussen e-mailbericht [`EmailField`](../emailfield) en veldtekstrepresentatie |
| [FontSubstitutes](../../groupdocs.conversion.options.load/emailloadoptions/fontsubstitutes) { get; set; } | Lijst met lettertypevervangers. |
| [Format](../../groupdocs.conversion.options.load/emailloadoptions/format) { get; set; } | Invoerdocument bestandstype. Is `null` totdat een formaat is ingesteld, dus test op `null` in plaats van tegen [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), waaraan het nooit gelijk is. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Invoerdocument bestandstype. |
| [MarginSettings](../../groupdocs.conversion.options.load/emailloadoptions/marginsettings) { get; set; } | Instellingen voor paginamarges |
| [OrientationSettings](../../groupdocs.conversion.options.load/emailloadoptions/orientationsettings) { get; set; } | Instellingen voor paginarichting |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/emailloadoptions/pagelayoutoptions) { get; set; } | Implementeert [`PageLayoutOptions`](../ipagelayoutoptions/pagelayoutoptions) |
| [PreserveOriginalDate](../../groupdocs.conversion.options.load/emailloadoptions/preserveoriginaldate) { get; set; } | Definieert of de originele datumheadertekst in het e-mailbericht moet worden behouden bij het opslaan of niet (Standaardwaarde is true) |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/emailloadoptions/resourceloadingtimeout) { get; set; } | Time‑out voor het laden van externe bronnen |
| [SizeSettings](../../groupdocs.conversion.options.load/emailloadoptions/sizesettings) { get; set; } | Instellingen voor paginagrootte |
| [SkipExternalResources](../../groupdocs.conversion.options.load/emailloadoptions/skipexternalresources) { get; set; } | Implementeert [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [TimeZoneOffset](../../groupdocs.conversion.options.load/emailloadoptions/timezoneoffset) { get; set; } | Haalt op of stelt de Coordinated Universal Time (UTC)-offset voor de berichtdatums in. Deze eigenschap definieert het tijdzoneverschil tussen de lokale tijd en UTC. |
| [UseDefaultAttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/usedefaultattachmenticons) { get; set; } | Haalt op of stelt in of standaardbijlage‑iconen moeten worden gebruikt. Standaard: true. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/emailloadoptions/whitelistedresources) { get; set; } | Implementeert [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/emailloadoptions/clone)() | Kloont de huidige instantie. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

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

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
