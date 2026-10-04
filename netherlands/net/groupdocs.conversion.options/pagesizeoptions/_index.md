---
title: "PageSizeOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Stelt opties voor die paginagrootte ondersteunen."
type: docs
weight: 2990
url: /nl/net/groupdocs.conversion.options/pagesizeoptions/
---
## PageSizeOptions class

Stelt opties voor die paginagrootte ondersteunen.

```csharp
public sealed class PageSizeOptions : ValueObject
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [PageSizeOptions](pagesizeoptions)() | Standaardconstructor. Initialiseert [`PageSize`](./pagesize) naar [`Unset`](../pagesize/unset). |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [PageHeight](../../groupdocs.conversion.options/pagesizeoptions/pageheight) { get; set; } | Paginahoogte in punten die moet worden toegepast vóór conversie. Indien ingesteld, wordt [`PageSize`](./pagesize) automatisch gewijzigd naar [`Custom`](../pagesize/custom). |
| [PageSize](../../groupdocs.conversion.options/pagesizeoptions/pagesize) { get; set; } | Implementeert [`PageSize`](../pagesize) |
| [PageWidth](../../groupdocs.conversion.options/pagesizeoptions/pagewidth) { get; set; } | Paginabreedte in punten die vóór de conversie moet worden toegepast. Indien ingesteld, wordt [`PageSize`](./pagesize) automatisch gewijzigd naar [`Custom`](../pagesize/custom). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options](../../groupdocs.conversion.options)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
