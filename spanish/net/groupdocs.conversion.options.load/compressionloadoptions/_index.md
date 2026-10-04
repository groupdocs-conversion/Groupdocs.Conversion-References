---
title: "CompressionLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para cargar documentos de compresión."
type: docs
weight: 2440
url: /es/net/groupdocs.conversion.options.load/compressionloadoptions/
---
## CompressionLoadOptions class

Opciones para cargar documentos de compresión.

```csharp
public sealed class CompressionLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CompressionLoadOptions](compressionloadoptions)() | Inicializa una nueva instancia de la clase [`CompressionLoadOptions`](../compressionloadoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/compressionloadoptions/convertowned) { get; } | Implementa [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) de solo lectura. Establecido en true. Los documentos propios serán convertidos |
| [ConvertOwner](../../groupdocs.conversion.options.load/compressionloadoptions/convertowner) { get; } | Implementa [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) de solo lectura. Establecido en false. El propietario no será convertido |
| [Depth](../../groupdocs.conversion.options.load/compressionloadoptions/depth) { get; set; } | Implementa [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth). Valor predeterminado: 3 |
| [Format](../../groupdocs.conversion.options.load/compressionloadoptions/format) { get; set; } | Tipo de archivo del documento de entrada. Es `null` hasta que se haya establecido un formato, por lo que debe probarse contra `null` en lugar de contra [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), con el que nunca es igual. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo de archivo del documento de entrada. |
| [Password](../../groupdocs.conversion.options.load/compressionloadoptions/password) { get; set; } | Establece la contraseña para cargar el documento protegido. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
