---
title: "RasterImageLoadOptions"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Opties voor het laden van afbeeldingsbestanden."
type: docs
weight: 2800
url: /nl/net/groupdocs.conversion.options.load/rasterimageloadoptions/
---
## RasterImageLoadOptions class

Opties voor het laden van afbeeldingsbestanden.

```csharp
public sealed class RasterImageLoadOptions : BaseImageLoadOptions
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [RasterImageLoadOptions](rasterimageloadoptions)() | Initialiseert een nieuw exemplaar van de klasse [`RasterImageLoadOptions`](../rasterimageloadoptions). |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CropArea](../../groupdocs.conversion.options.load/rasterimageloadoptions/croparea) { get; set; } | Bijsnijden van het afbeeldingsgebied vóór conversie |
| [DefaultFont](../../groupdocs.conversion.options.load/baseimageloadoptions/defaultfont) { get; set; } | Standaardlettertype voor Psd-, Emf- en Wmf‑documenttypen. Het volgende lettertype wordt gebruikt als er een lettertype ontbreekt. |
| [Format](../../groupdocs.conversion.options.load/rasterimageloadoptions/format) { get; set; } | Invoerdocument bestandstype. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Invoerdocument bestandstype. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/baseimageloadoptions/resetfontfolders) { get; set; } | Reset lettertype‑mappen vóór het laden van het document |
| [VectorizationOptions](../../groupdocs.conversion.options.load/rasterimageloadoptions/vectorizationoptions) { get; set; } | Stelt vectorisatie-opties in |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |
| [SetHeicConnector](../../groupdocs.conversion.options.load/rasterimageloadoptions/setheicconnector)(IHeicConnector) | Stel Heic-afbeeldingsconnector in |
| [SetOcrConnector](../../groupdocs.conversion.options.load/rasterimageloadoptions/setocrconnector)(IOcrConnector) | Stel afbeelding OCR-connector in |

### Zie ook

* class [BaseImageLoadOptions](../baseimageloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
