---
title: "EmailLoadOptions"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Optionen zum Laden von E-Mail-Dokumenten."
type: docs
weight: 2500
url: /de/net/groupdocs.conversion.options.load/emailloadoptions/
---
## EmailLoadOptions class

Optionen zum Laden von E-Mail-Dokumenten.

```csharp
public sealed class EmailLoadOptions : LoadOptions, ICustomCssStyleOptions, 
    IDocumentsContainerLoadOptions, IFontSubstituteLoadOptions, IPageLayoutOptions, 
    IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, IResourceLoadingOptions
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [EmailLoadOptions](emailloadoptions)() | Initialisiert eine neue Instanz der Klasse [`EmailLoadOptions`](../emailloadoptions). |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/attachmenticons) { get; set; } | Liest oder setzt die Liste der Anhangssymbole. Die Liste kann angepasst werden, um spezifische Symbole für verschiedene Dateitypen bereitzustellen. Standardmäßig enthält sie gängige Dateitypsymbole. |
| [ConvertOwned](../../groupdocs.conversion.options.load/emailloadoptions/convertowned) { get; set; } | Implementiert [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned). Standardwert ist true. |
| [ConvertOwner](../../groupdocs.conversion.options.load/emailloadoptions/convertowner) { get; set; } | Implementiert [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner). Standard ist true. |
| [CustomCssStyle](../../groupdocs.conversion.options.load/emailloadoptions/customcssstyle) { get; set; } | Implementiert [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [DefaultFont](../../groupdocs.conversion.options.load/emailloadoptions/defaultfont) { get; set; } | Standardschriftart für E‑Mail‑Dokumente. Die folgende Schriftart wird verwendet, wenn eine Schriftart fehlt. |
| [Depth](../../groupdocs.conversion.options.load/emailloadoptions/depth) { get; set; } | Implementiert [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth). Standard: 1. |
| [DisplayAttachments](../../groupdocs.conversion.options.load/emailloadoptions/displayattachments) { get; set; } | Option zum Anzeigen oder Ausblenden von Anhängen im Header. Standard: true. |
| [DisplayBccEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaybccemailaddress) { get; set; } | Option zum Anzeigen oder Ausblenden der "Bcc"‑E‑Mail‑Adresse. Standard: false. |
| [DisplayCcEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayccemailaddress) { get; set; } | Option zum Anzeigen oder Ausblenden der "Cc"‑E‑Mail‑Adresse. Standard: false. |
| [DisplayEmailAddresses](../../groupdocs.conversion.options.load/emailloadoptions/displayemailaddresses) { get; set; } | Option zur Steuerung, ob E‑Mail‑Adressen neben Namen angezeigt werden. Beispiel: "John Doe &lt;john.doe@sample.com&gt;" oder nur "John Doe." Standard: true. |
| [DisplayFromEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayfromemailaddress) { get; set; } | Option zum Anzeigen oder Ausblenden der "from"‑E‑Mail‑Adresse. Standard: true. |
| [DisplayHeader](../../groupdocs.conversion.options.load/emailloadoptions/displayheader) { get; set; } | Option zum Anzeigen oder Ausblenden des E‑Mail‑Headers. Standard: true. |
| [DisplaySent](../../groupdocs.conversion.options.load/emailloadoptions/displaysent) { get; set; } | Option zum Anzeigen oder Ausblenden von Sendedatum/-zeit im Header. Standard: true. |
| [DisplaySubject](../../groupdocs.conversion.options.load/emailloadoptions/displaysubject) { get; set; } | Option zum Anzeigen oder Ausblenden des Betreffs im Header. Standard: true. |
| [DisplayToEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaytoemailaddress) { get; set; } | Option zum Anzeigen oder Ausblenden der "to"‑E‑Mail‑Adresse. Standard: true. |
| [FieldTextMap](../../groupdocs.conversion.options.load/emailloadoptions/fieldtextmap) { get; set; } | Die Zuordnung zwischen E‑Mail‑Nachricht [`EmailField`](../emailfield) und der Textdarstellung des Feldes |
| [FontSubstitutes](../../groupdocs.conversion.options.load/emailloadoptions/fontsubstitutes) { get; set; } | Liste von Schriftart‑Ersatz. |
| [Format](../../groupdocs.conversion.options.load/emailloadoptions/format) { get; set; } | Dateityp des Eingabedokuments. Ist `null`, bis ein Format festgelegt wurde, daher prüfen Sie auf `null` anstatt gegen [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) zu vergleichen, was niemals zutrifft. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Dateityp des Eingabedokuments. |
| [MarginSettings](../../groupdocs.conversion.options.load/emailloadoptions/marginsettings) { get; set; } | Seitenrand-Einstellungen |
| [OrientationSettings](../../groupdocs.conversion.options.load/emailloadoptions/orientationsettings) { get; set; } | Einstellungen für die Seitenausrichtung |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/emailloadoptions/pagelayoutoptions) { get; set; } | Implementiert [`PageLayoutOptions`](../ipagelayoutoptions/pagelayoutoptions). |
| [PreserveOriginalDate](../../groupdocs.conversion.options.load/emailloadoptions/preserveoriginaldate) { get; set; } | Definiert, ob die ursprüngliche Datums‑Header‑Zeichenkette in der E‑Mail‑Nachricht beim Speichern beibehalten werden muss oder nicht (Standardwert ist true) |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/emailloadoptions/resourceloadingtimeout) { get; set; } | Zeitlimit für das Laden externer Ressourcen |
| [SizeSettings](../../groupdocs.conversion.options.load/emailloadoptions/sizesettings) { get; set; } | Seitengröße-Einstellungen |
| [SkipExternalResources](../../groupdocs.conversion.options.load/emailloadoptions/skipexternalresources) { get; set; } | Implementiert [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [TimeZoneOffset](../../groupdocs.conversion.options.load/emailloadoptions/timezoneoffset) { get; set; } | Liest oder setzt den Coordinated Universal Time (UTC)-Offset für die Nachrichten­daten. Diese Eigenschaft definiert den Zeitzonenunterschied zwischen der lokalen Zeit und UTC. |
| [UseDefaultAttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/usedefaultattachmenticons) { get; set; } | Liest oder setzt, ob Standard‑Anhangssymbole verwendet werden sollen. Standard: true. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/emailloadoptions/whitelistedresources) { get; set; } | Implementiert [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/emailloadoptions/clone)() | Klont die aktuelle Instanz. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bestimmt, ob zwei Objektinstanzen gleich sind. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als Standard-Hashfunktion. |

### Siehe auch

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

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
