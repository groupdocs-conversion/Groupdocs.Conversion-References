---
title: "OlmLoadOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Opties voor het laden van Olm-documenten."
type: docs
weight: 2700
url: /nl/net/groupdocs.conversion.options.load/olmloadoptions/
---
## OlmLoadOptions class

Opties voor het laden van Olm-documenten.

```csharp
public sealed class OlmLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [OlmLoadOptions](olmloadoptions)() | Initialiseert een nieuw exemplaar van de [`OlmLoadOptions`](../olmloadoptions) klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/olmloadoptions/convertowned) { get; } | Implementeert [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Alleen-lezen. Ingesteld op true. De eigendomsdocumenten worden geconverteerd. |
| [ConvertOwner](../../groupdocs.conversion.options.load/olmloadoptions/convertowner) { get; } | Implementeert [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Alleen-lezen. Ingesteld op false. De eigenaar wordt niet geconverteerd. |
| [Depth](../../groupdocs.conversion.options.load/olmloadoptions/depth) { get; set; } | Implementeert [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Standaard: 3 |
| [Folder](../../groupdocs.conversion.options.load/olmloadoptions/folder) { get; set; } | Map die verwerkt moet worden. Standaard is Inbox. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Invoerdocument bestandstype. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/olmloadoptions/clone)() | Kloont de huidige instantie. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
