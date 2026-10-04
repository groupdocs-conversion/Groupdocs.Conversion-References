---
title: "MarkdownOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Opties voor conversie naar markdown‑bestandtype."
type: docs
weight: 2010
url: /nl/net/groupdocs.conversion.options.convert/markdownoptions/
---
## MarkdownOptions class

Opties voor conversie naar markdown‑bestandtype.

```csharp
public sealed class MarkdownOptions : ValueObject
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [MarkdownOptions](markdownoptions)() | Initialiseert een nieuw exemplaar van de klasse [`MarkdownOptions`](../markdownoptions). |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.conversion.options.convert/markdownoptions/exportimagesasbase64) { get; set; } | Exporteer afbeeldingen als base64. Standaard is true. Wordt genegeerd wanneer [`ImageSavingCallback`](./imagesavingcallback) is ingesteld. |
| [ImageSavingCallback](../../groupdocs.conversion.options.convert/markdownoptions/imagesavingcallback) { get; set; } | Callback wordt eenmaal per afbeelding aangeroepen tijdens het opslaan van Markdown. Hiermee kan de aanroeper afbeeldingen extern bewaren en de URI in het document vervangen. Heeft voorrang op [`ExportImagesAsBase64`](./exportimagesasbase64) wanneer niet null. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
