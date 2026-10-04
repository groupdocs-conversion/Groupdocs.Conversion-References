---
title: "PublisherLoadOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Opties voor het laden van Publisher-documenten."
type: docs
weight: 2790
url: /nl/net/groupdocs.conversion.options.load/publisherloadoptions/
---
## PublisherLoadOptions class

Opties voor het laden van Publisher-documenten.

```csharp
public class PublisherLoadOptions : LoadOptions, IFontSubstituteLoadOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [PublisherLoadOptions](publisherloadoptions)() | Initialiseert een nieuw exemplaar van de [`PublisherLoadOptions`](../publisherloadoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/publisherloadoptions/defaultfont) { get; set; } | Standaardlettertype voor Publisher‑documenten. Het volgende lettertype wordt gebruikt als er een lettertype ontbreekt. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/publisherloadoptions/fontsubstitutes) { get; set; } | Vervang specifieke lettertypen bij het converteren van een Publisher‑document. |
| [Format](../../groupdocs.conversion.options.load/publisherloadoptions/format) { get; } | Invoerdocument bestandstype. Is `null` totdat een formaat is ingesteld, dus test op `null` in plaats van tegen [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), waaraan het nooit gelijk is. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Invoerdocument bestandstype. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [LoadOptions](../loadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
