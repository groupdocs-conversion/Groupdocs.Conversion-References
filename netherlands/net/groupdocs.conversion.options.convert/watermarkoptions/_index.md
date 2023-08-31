---
title: WatermarkOptions
second_title: GroupDocs.Conversion voor .NET API-referentie
description: Opties voor instellingen watermerk naar het geconverteerde document
type: docs
weight: 1960
url: /nl/net/groupdocs.conversion.options.convert/watermarkoptions/
---
## WatermarkOptions class

Opties voor instellingen watermerk naar het geconverteerde document

```csharp
public abstract class WatermarkOptions : ValueObject, ICloneable
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AutoAlign](../../groupdocs.conversion.options.convert/watermarkoptions/autoalign) { get; set; } | Het watermerk automatisch schalen. Als de waarde waar is, worden de positie en het formaat automatisch berekend om op het paginaformaat te passen. |
| [Background](../../groupdocs.conversion.options.convert/watermarkoptions/background) { get; set; } | Geeft aan dat het watermerk als achtergrond is gestempeld. Als de waarde waar is, wordt het watermerk onderaan gelegd. Standaard is dit false en wordt het watermerk er bovenop gelegd. |
| [Height](../../groupdocs.conversion.options.convert/watermarkoptions/height) { get; set; } | Hoogte watermerk |
| [Left](../../groupdocs.conversion.options.convert/watermarkoptions/left) { get; set; } | Watermerk linkerpositie |
| [RotationAngle](../../groupdocs.conversion.options.convert/watermarkoptions/rotationangle) { get; set; } | Rotatiehoek watermerk |
| [Top](../../groupdocs.conversion.options.convert/watermarkoptions/top) { get; set; } | Watermerk bovenpositie |
| [Transparency](../../groupdocs.conversion.options.convert/watermarkoptions/transparency) { get; set; } | Watermerktransparantie. Waarde tussen 0 en 1. Waarde 0 is volledig zichtbaar, waarde 1 is onzichtbaar. |
| [Width](../../groupdocs.conversion.options.convert/watermarkoptions/width) { get; set; } | Breedte watermerk |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/watermarkoptions/clone)() | Huidige instantie klonen |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* naamruimte [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->