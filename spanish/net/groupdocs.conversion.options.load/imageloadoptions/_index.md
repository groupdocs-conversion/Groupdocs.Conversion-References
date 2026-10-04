---
title: "ImageLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para cargar documentos de Imagen."
type: docs
weight: 2650
url: /es/net/groupdocs.conversion.options.load/imageloadoptions/
---
## ImageLoadOptions class

Opciones para cargar documentos de Imagen.

```csharp
public sealed class ImageLoadOptions : BaseImageLoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageLoadOptions](imageloadoptions)() | Inicializa una nueva instancia de la clase [`ImageLoadOptions`](../imageloadoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/baseimageloadoptions/defaultfont) { get; set; } | Fuente predeterminada para los tipos de documento Psd, Emf, Wmf. La siguiente fuente se utilizará si falta una fuente. |
| [Format](../../groupdocs.conversion.options.load/imageloadoptions/format) { get; set; } | Tipo de archivo del documento de entrada. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo de archivo del documento de entrada. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/baseimageloadoptions/resetfontfolders) { get; set; } | Restablece las carpetas de fuentes antes de cargar el documento |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [BaseImageLoadOptions](../baseimageloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
