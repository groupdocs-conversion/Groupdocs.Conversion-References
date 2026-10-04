---
title: "VideoLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para cargar documentos de video."
type: docs
weight: 2910
url: /es/net/groupdocs.conversion.options.load/videoloadoptions/
---
## VideoLoadOptions class

Opciones para cargar documentos de video.

```csharp
public sealed class VideoLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [VideoLoadOptions](videoloadoptions)() | Inicializa una nueva instancia de la clase [`VideoLoadOptions`](../videoloadoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/videoloadoptions/format) { get; set; } | Tipo de archivo del documento de entrada. Es `null` hasta que se haya establecido un formato, por lo que debe probarse contra `null` en lugar de contra [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), con el que nunca es igual. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo de archivo del documento de entrada. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |
| [SetVideoConnector](../../groupdocs.conversion.options.load/videoloadoptions/setvideoconnector)(IVideoConnector) | Establece el conector del documento de video |

### Ver también

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
