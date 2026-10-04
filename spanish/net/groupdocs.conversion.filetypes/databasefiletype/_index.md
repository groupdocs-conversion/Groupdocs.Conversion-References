---
title: "DatabaseFileType"
second_title: "Referencia de API de GroupDocs.Conversion para .NET"
description: "Define documentos de base de datos. Incluye los siguientes tipos de archivo Nsf./databasefiletype/nsfLog./databasefiletype/logSql./databasefiletype/sql"
type: docs
weight: 1090
url: /es/net/groupdocs.conversion.filetypes/databasefiletype/
---
## DatabaseFileType class

Define documentos de base de datos. Incluye los siguientes tipos de archivo: [`Nsf`](./nsf)[`Log`](./log)[`Sql`](./sql)

```csharp
public sealed class DatabaseFileType : FileType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [DatabaseFileType](databasefiletype)() | Constructor de serialización |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Descripción del tipo de archivo |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | La extensión del archivo |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La familia del archivo |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | El formato del archivo |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compara el objeto actual con otro. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementa [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sirve como la función hash predeterminada. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representación de cadena |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Log](../../groupdocs.conversion.filetypes/databasefiletype/log) | Un archivo con extensión .log contiene una lista de texto plano con marca de tiempo. Normalmente, ciertos detalles de actividad son registrados por el software o los sistemas operativos para ayudar a los desarrolladores o usuarios a rastrear lo que sucedía en un período de tiempo determinado. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/database/log). |
| static readonly [Nsf](../../groupdocs.conversion.filetypes/databasefiletype/nsf) | Un archivo con extensión .nsf (Notes Storage Facility) es un formato de archivo de base de datos utilizado por el software IBM Notes, que antes se conocía como Lotus Notes. Define el esquema para almacenar diferentes tipos de objetos como correos electrónicos, citas, documentos, formularios y vistas. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/database/nsf). |
| static readonly [Sql](../../groupdocs.conversion.filetypes/databasefiletype/sql) | Un archivo con extensión .sql es un archivo Structured Query Language (SQL) que contiene código para trabajar con bases de datos relacionales. Se usa para escribir sentencias SQL para operaciones CRUD (Crear, Leer, Actualizar y Eliminar) en bases de datos. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/database/sql). |

### Ver también

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.conversion.dll -->
