---
title: "ConvertOptionsTFileType"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Abstracte generieke conversieoptiesklasse."
type: docs
weight: 1770
url: /nl/net/groupdocs.conversion.options.convert/convertoptions-1/
---
## ConvertOptions&lt;TFileType&gt; class

Abstracte generieke conversieoptiesklasse.

```csharp
public abstract class ConvertOptions<TFileType> : ConvertOptions
    where TFileType : FileType
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementeert [`Format`](../iconvertoptions/format) |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Kloont de huidige opties-instantie. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [ConvertOptions](../convertoptions)
* class [FileType](../../groupdocs.conversion.filetypes/filetype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
