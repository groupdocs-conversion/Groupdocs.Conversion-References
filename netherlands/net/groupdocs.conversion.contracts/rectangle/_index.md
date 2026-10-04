---
title: "Rechthoek"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Stelt een rechthoek voor die door zijn randen is gedefinieerd voor bijsnijdende doeleinden."
type: docs
weight: 580
url: /nl/net/groupdocs.conversion.contracts/rectangle/
---
## Rectangle class

Stelt een rechthoek voor die door zijn randen is gedefinieerd voor bijsnijdende doeleinden.

```csharp
public sealed class Rectangle : ValueObject
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Rectangle](rectangle)(int, int, int, int) | Initialiseert een nieuw exemplaar van de [`Rectangle`](../rectangle) struct met opgegeven randen. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Bottom](../../groupdocs.conversion.contracts/rectangle/bottom) { get; } | Haalt de onderrand van de rechthoek op. |
| [Height](../../groupdocs.conversion.contracts/rectangle/height) { get; } | Haalt de hoogte van de rechthoek op op basis van de boven- en onderrand. |
| [Left](../../groupdocs.conversion.contracts/rectangle/left) { get; } | Haalt de linkerrand van de rechthoek op. |
| [Right](../../groupdocs.conversion.contracts/rectangle/right) { get; } | Haalt de rechterrand van de rechthoek op. |
| [Top](../../groupdocs.conversion.contracts/rectangle/top) { get; } | Haalt de bovenrand van de rechthoek op. |
| [Width](../../groupdocs.conversion.contracts/rectangle/width) { get; } | Haalt de breedte van de rechthoek op op basis van de linker- en rechterrand. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Crop](../../groupdocs.conversion.contracts/rectangle/crop)(int, int, int, int) | Maakt een bijgesneden versie van de huidige rechthoek door opgegeven marges te verwijderen. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |
| override [ToString](../../groupdocs.conversion.contracts/rectangle/tostring)() | Retourneert een stringrepresentatie van de rechthoek. |

### Zie ook

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
