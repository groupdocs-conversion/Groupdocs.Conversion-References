---
title: "CommonConvertOptionsTFileType"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Clase abstracta genérica de opciones comunes de conversión."
type: docs
weight: 1740
url: /es/net/groupdocs.conversion.options.convert/commonconvertoptions-1/
---
## CommonConvertOptions&lt;TFileType&gt; class

Clase abstracta genérica de opciones comunes de conversión.

```csharp
public abstract class CommonConvertOptions<TFileType> : ConvertOptions<TFileType>, 
    IPagedConvertOptions, IPageRangedConvertOptions, IWatermarkedConvertOptions
    where TFileType : FileType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | El tipo de archivo deseado al que debe convertirse el documento de entrada. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementa [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Implementa [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Implementa [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Implementa [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Implementa [`Watermark`](../iwatermarkedconvertoptions/watermark) |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona la instancia actual de opciones. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* interface [IPagedConvertOptions](../ipagedconvertoptions)
* interface [IPageRangedConvertOptions](../ipagerangedconvertoptions)
* interface [IWatermarkedConvertOptions](../iwatermarkedconvertoptions)
* class [FileType](../../groupdocs.conversion.filetypes/filetype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
