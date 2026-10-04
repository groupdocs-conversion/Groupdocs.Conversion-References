---
title: "ThreeDConvertOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones de conversión al tipo 3D."
type: docs
weight: 2250
url: /es/net/groupdocs.conversion.options.convert/threedconvertoptions/
---
## ThreeDConvertOptions class

Opciones de conversión al tipo 3D.

```csharp
public class ThreeDConvertOptions : ConvertOptions<ThreeDFileType>, IPagedConvertOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ThreeDConvertOptions](threedconvertoptions)() | Inicializa una nueva instancia de la clase [`ThreeDConvertOptions`](../threedconvertoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | El tipo de archivo deseado al que debe convertirse el documento de entrada. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Implementa [`Format`](../iconvertoptions/format) |
| [PageNumber](../../groupdocs.conversion.options.convert/threedconvertoptions/pagenumber) { get; set; } | Implementa [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [PagesCount](../../groupdocs.conversion.options.convert/threedconvertoptions/pagescount) { get; set; } | Implementa [`PagesCount`](../ipagedconvertoptions/pagescount) |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona la instancia actual de opciones. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [ThreeDFileType](../../groupdocs.conversion.filetypes/threedfiletype)
* interface [IPagedConvertOptions](../ipagedconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
