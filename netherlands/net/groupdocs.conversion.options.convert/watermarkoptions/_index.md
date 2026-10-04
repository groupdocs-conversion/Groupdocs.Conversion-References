---
title: "WatermarkOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Opties voor het instellen van een watermerk op het geconverteerde document"
type: docs
weight: 2300
url: /nl/net/groupdocs.conversion.options.convert/watermarkoptions/
---
## WatermarkOptions class

Opties voor het instellen van een watermerk op het geconverteerde document

```csharp
public abstract class WatermarkOptions : ValueObject, ICloneable
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AutoAlign](../../groupdocs.conversion.options.convert/watermarkoptions/autoalign) { get; set; } | Schaal het watermerk automatisch. Als de waarde true is, worden positie en grootte automatisch berekend om op de paginagrootte te passen. |
| [Background](../../groupdocs.conversion.options.convert/watermarkoptions/background) { get; set; } | Geeft aan dat het watermerk als achtergrond wordt gestempeld. Als de waarde true is, wordt het watermerk onderaan geplaatst. Standaard is false en wordt het watermerk bovenaan geplaatst. |
| [Height](../../groupdocs.conversion.options.convert/watermarkoptions/height) { get; set; } | Watermerkhoogte |
| [Left](../../groupdocs.conversion.options.convert/watermarkoptions/left) { get; set; } | Linkerpositie van watermerk |
| [RotationAngle](../../groupdocs.conversion.options.convert/watermarkoptions/rotationangle) { get; set; } | Rotatiehoek van watermerk |
| [Top](../../groupdocs.conversion.options.convert/watermarkoptions/top) { get; set; } | Bovenste positie van watermerk |
| [Transparency](../../groupdocs.conversion.options.convert/watermarkoptions/transparency) { get; set; } | Watermerktransparantie. Waarde tussen 0 en 1. Waarde 0 is volledig zichtbaar, waarde 1 is onzichtbaar. |
| [Width](../../groupdocs.conversion.options.convert/watermarkoptions/width) { get; set; } | Watermerkbreedte |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/watermarkoptions/clone)() | Kloon huidige instantie |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
