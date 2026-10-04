---
title: "BaseImageLoadOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Opties voor het laden van afbeeldingsbestanden."
type: docs
weight: 2400
url: /nl/net/groupdocs.conversion.options.load/baseimageloadoptions/
---
## BaseImageLoadOptions class

Opties voor het laden van afbeeldingsbestanden.

```csharp
public abstract class BaseImageLoadOptions : LoadOptions
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/baseimageloadoptions/defaultfont) { get; set; } | Standaardlettertype voor Psd-, Emf- en Wmf‑documenttypen. Het volgende lettertype wordt gebruikt als er een lettertype ontbreekt. |
| [Format](../../groupdocs.conversion.options.load/baseimageloadoptions/format) { get; set; } | Invoerdocument bestandstype. Is `null` totdat een formaat is ingesteld, dus test op `null` in plaats van tegen [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), waaraan het nooit gelijk is. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Invoerdocument bestandstype. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/baseimageloadoptions/resetfontfolders) { get; set; } | Reset lettertype‑mappen vóór het laden van het document |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
