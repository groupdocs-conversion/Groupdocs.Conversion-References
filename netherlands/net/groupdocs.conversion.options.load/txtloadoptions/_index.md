---
title: "TxtLoadOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Opties voor het laden van Txt-documenten."
type: docs
weight: 2870
url: /nl/net/groupdocs.conversion.options.load/txtloadoptions/
---
## TxtLoadOptions class

Opties voor het laden van Txt-documenten.

```csharp
public sealed class TxtLoadOptions : LoadOptions, IPageMarginOptions, IPageSizeOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [TxtLoadOptions](txtloadoptions)() | Initialiseert een nieuwe instantie van de [`TxtLoadOptions`](../txtloadoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/txtloadoptions/defaultfont) { get; set; } | Lettertype om te gebruiken bij het renderen van platte tekstinhoud tijdens conversie. Aangezien TXT‑bestanden geen lettertype‑informatie bevatten, specificeert deze eigenschap het weergavelettertype voor de tekstinhoud. Standaard: Arial 10pt. |
| [DetectNumberingWithWhitespaces](../../groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces) { get; set; } | Staat toe om op te geven hoe genummerde lijstitems worden herkend wanneer een platte‑tekstdocument wordt geconverteerd. De standaardwaarde is true. |
| [Encoding](../../groupdocs.conversion.options.load/txtloadoptions/encoding) { get; set; } | Haalt of stelt de codering in die wordt gebruikt bij het laden van een Txt‑document. Kan null zijn. Standaard is null. |
| [Format](../../groupdocs.conversion.options.load/txtloadoptions/format) { get; } | Invoerdocument bestandstype. Is `null` totdat een formaat is ingesteld, dus test op `null` in plaats van tegen [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), waaraan het nooit gelijk is. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Invoerdocument bestandstype. |
| [LeadingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/leadingspacesoptions) { get; set; } | Haalt of stelt de voorkeuroptie voor het behandelen van voorloopspaties in. Standaardwaarde is [`ConvertToIndent`](../txtleadingspacesoptions/converttoindent). |
| [MarginSettings](../../groupdocs.conversion.options.load/txtloadoptions/marginsettings) { get; set; } | Instellingen voor paginamarges |
| [SizeSettings](../../groupdocs.conversion.options.load/txtloadoptions/sizesettings) { get; set; } | Instellingen voor paginagrootte |
| [TrailingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/trailingspacesoptions) { get; set; } | Haalt of stelt de voorkeuroptie voor het behandelen van naloopspaties in. Standaardwaarde is [`Trim`](../txttrailingspacesoptions/trim). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Opmerkingen

**Font Configuration for Plain Text:**

Aangezien TXT‑bestanden geen lettertype‑informatie bevatten, gebruik DefaultTextFont om te specificeren

het lettertype voor het renderen van de platte‑tekstinhoud tijdens conversie.

### Zie ook

* class [LoadOptions](../loadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
