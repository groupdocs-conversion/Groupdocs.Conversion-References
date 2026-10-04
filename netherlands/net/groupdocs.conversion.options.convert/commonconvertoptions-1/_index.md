---
title: "CommonConvertOptionsTFileType"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Abstracte generieke algemene conversieoptiesklasse."
type: docs
weight: 1740
url: /nl/net/groupdocs.conversion.options.convert/commonconvertoptions-1/
---
## CommonConvertOptions&lt;TFileType&gt; class

Abstracte generieke algemene conversieoptiesklasse.

```csharp
public abstract class CommonConvertOptions<TFileType> : ConvertOptions<TFileType>, 
    IPagedConvertOptions, IPageRangedConvertOptions, IWatermarkedConvertOptions
    where TFileType : FileType
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Het gewenste bestandstype waarnaar het invoerdocument moet worden geconverteerd. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementeert [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementeert [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementeert [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementeert [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementeert [`Watermark`](../iwatermarkedconvertoptions/watermark) |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Kloont de huidige opties-instantie. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Bepaalt of twee objectinstanties gelijk zijn. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Bepaalt of twee objectinstanties gelijk zijn. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Dient als de standaard hash-functie. |

### Zie ook

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* interface [IPagedConvertOptions](../ipagedconvertoptions)
* interface [IPageRangedConvertOptions](../ipagerangedconvertoptions)
* interface [IWatermarkedConvertOptions](../iwatermarkedconvertoptions)
* class [FileType](../../groupdocs.conversion.filetypes/filetype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
