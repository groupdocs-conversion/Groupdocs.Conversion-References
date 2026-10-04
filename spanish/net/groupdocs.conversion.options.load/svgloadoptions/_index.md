---
title: "SvgLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para cargar documentos Svg."
type: docs
weight: 2830
url: /es/net/groupdocs.conversion.options.load/svgloadoptions/
---
## SvgLoadOptions class

Opciones para cargar documentos Svg.

```csharp
public class SvgLoadOptions : LoadOptions, IResourceLoadingOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SvgLoadOptions](svgloadoptions)() | Inicializa una nueva instancia de la clase [`SvgLoadOptions`](../svgloadoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CropToContentBounds](../../groupdocs.conversion.options.load/svgloadoptions/croptocontentbounds) { get; set; } | Obtiene o establece un valor que indica si se recorta el cuadro delimitador SVG a los límites del contenido antes de la conversión. El valor predeterminado es false. |
| [Format](../../groupdocs.conversion.options.load/svgloadoptions/format) { get; set; } | Tipo de archivo del documento de entrada. Es `null` hasta que se haya establecido un formato, por lo que debe probarse contra `null` en lugar de contra [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), con el que nunca es igual. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo de archivo del documento de entrada. |
| [MinimumHeight](../../groupdocs.conversion.options.load/svgloadoptions/minimumheight) { get; set; } | Establece la altura mínima para convertir el documento SVG. Se utiliza al convertir a formatos raster. El valor predeterminado es 600. |
| [MinimumWidth](../../groupdocs.conversion.options.load/svgloadoptions/minimumwidth) { get; set; } | Establece el ancho mínimo para convertir el documento SVG. Se utiliza al convertir a formatos raster. El valor predeterminado es 800. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/svgloadoptions/skipexternalresources) { get; set; } | Implementa [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [WhitelistedResources](../../groupdocs.conversion.options.load/svgloadoptions/whitelistedresources) { get; set; } | Recursos externos que siempre se cargarán. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [LoadOptions](../loadoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
