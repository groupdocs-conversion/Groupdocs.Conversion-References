---
title: WebConvertOptions
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Opciones de conversión a archivo tipo Web.
type: docs
weight: 1980
url: /es/net/groupdocs.conversion.options.convert/webconvertoptions/
---
## WebConvertOptions class

Opciones de conversión a archivo tipo Web.

```csharp
public class WebConvertOptions : CommonConvertOptions<WebFileType>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WebConvertOptions](webconvertoptions)() | Inicializa una nueva instancia de[`WebConvertOptions`](../webconvertoptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [FixedLayout](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayout) { get; set; } | Si`verdadero` se utilizará un diseño fijo, por ejemplo, elementos html absolutamente posicionados Predeterminado: true |
| [FixedLayoutShowBorders](../../groupdocs.conversion.options.convert/webconvertoptions/fixedlayoutshowborders) { get; set; } | Mostrar bordes de página al convertir a diseño fijo. El valor predeterminado es Verdadero. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | El tipo de archivo deseado al que se debe convertir el documento de entrada. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | El tipo de archivo deseado al que se debe convertir el documento de entrada. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | El número de página desde el que iniciar la conversión. |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | La lista de índices de página que se van a convertir. Debe especificarse para convertir páginas específicas. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Número de páginas para convertir a partir de`Número de página` . |
| [UsePdf](../../groupdocs.conversion.options.convert/webconvertoptions/usepdf) { get; set; } | Si`verdadero` , la entrada primero se convierte a PDF y luego al formato deseado |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Opciones específicas de marca de agua |
| [Zoom](../../groupdocs.conversion.options.convert/webconvertoptions/zoom) { get; set; } | Especifica el nivel de zoom en porcentaje. El valor predeterminado es 100. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Clona la instancia de opciones actual. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WebFileType](../../groupdocs.conversion.filetypes/webfiletype)
* espacio de nombres [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* asamblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
