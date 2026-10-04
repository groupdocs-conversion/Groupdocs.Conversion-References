---
title: "GisLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para cargar documentos GIS."
type: docs
weight: 2540
url: /es/net/groupdocs.conversion.options.load/gisloadoptions/
---
## GisLoadOptions class

Opciones para cargar documentos GIS.

```csharp
public class GisLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [GisLoadOptions](gisloadoptions)() | Inicializa una nueva instancia de la clase [`GisLoadOptions`](../gisloadoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/gisloadoptions/format) { get; set; } | Tipo de archivo del documento de entrada. Es `null` hasta que se haya establecido un formato, por lo que debe probarse contra `null` en lugar de contra [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), con el que nunca es igual. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo de archivo del documento de entrada. |
| [Height](../../groupdocs.conversion.options.load/gisloadoptions/height) { get; set; } | Establece la altura de página deseada para la conversión del documento GIS. El valor predeterminado es 1000. |
| [Width](../../groupdocs.conversion.options.load/gisloadoptions/width) { get; set; } | Establece el ancho de página deseado para la conversión del documento GIS. El valor predeterminado es 1000. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
