---
title: "PersonalStorageLoadOptions"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Opciones para cargar documentos de almacenamiento personal."
type: docs
weight: 2750
url: /es/net/groupdocs.conversion.options.load/personalstorageloadoptions/
---
## PersonalStorageLoadOptions class

Opciones para cargar documentos de almacenamiento personal.

```csharp
public sealed class PersonalStorageLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PersonalStorageLoadOptions](personalstorageloadoptions)() | Inicializa una nueva instancia de la clase [`PersonalStorageLoadOptions`](../personalstorageloadoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/personalstorageloadoptions/convertowned) { get; } | Implementa [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) de solo lectura. Establecido en true. Los documentos propios serán convertidos |
| [ConvertOwner](../../groupdocs.conversion.options.load/personalstorageloadoptions/convertowner) { get; } | Implementa [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) de solo lectura. Establecido en false. El propietario no será convertido |
| [Depth](../../groupdocs.conversion.options.load/personalstorageloadoptions/depth) { get; set; } | Implementa [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth). Valor predeterminado: 3 |
| [Folder](../../groupdocs.conversion.options.load/personalstorageloadoptions/folder) { get; set; } | Carpeta que se procesará. Predeterminado es Inbox. |
| [Format](../../groupdocs.conversion.options.load/personalstorageloadoptions/format) { get; set; } | Tipo de archivo del documento de entrada. Es `null` hasta que se haya establecido un formato, por lo que debe probarse contra `null` en lugar de contra [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown), con el que nunca es igual. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo de archivo del documento de entrada. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/personalstorageloadoptions/clone)() | Clona la instancia actual. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina si dos instancias de objeto son iguales. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Sirve como la función hash predeterminada. |

### Ver también

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
