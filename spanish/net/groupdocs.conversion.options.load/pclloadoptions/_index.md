---
title: "PclLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para cargar documentos Pcl."
type: docs
weight: 2730
url: /es/net/groupdocs.conversion.options.load/pclloadoptions/
---
## PclLoadOptions class

Opciones para cargar documentos Pcl.

```csharp
public sealed class PclLoadOptions : LoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PclLoadOptions](pclloadoptions)() | Inicializa una nueva instancia de la clase [`PclLoadOptions`](../pclloadoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/pclloadoptions/format) { get; } | Tipo de archivo del documento de entrada. Es `null` hasta que se haya establecido un formato, por lo que debe probarse contra `null` en lugar de contra [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), con el que nunca es igual. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo de archivo del documento de entrada. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/pclloadoptions/resetfontfolders) { get; set; } | Restablece las carpetas de fuentes antes de cargar el documento |

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
