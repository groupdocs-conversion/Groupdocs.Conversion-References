---
title: DatabaseFileType
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Define los documentos de la base de datos. Incluye los siguientes tipos de archivo Nsf./databasefiletype/nsfLog./databasefiletype/logSql./databasefiletype/sql
type: docs
weight: 890
url: /es/net/groupdocs.conversion.filetypes/databasefiletype/
---
## DatabaseFileType class

Define los documentos de la base de datos. Incluye los siguientes tipos de archivo: [`Nsf`](./nsf)[`Log`](./log)[`Sql`](./sql)

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
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | El archivo family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | El formato de archivo |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compara el objeto actual con otro. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Determina si dos instancias de objeto son iguales. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sirve como la función hash predeterminada. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representación de cadena |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Log](../../groupdocs.conversion.filetypes/databasefiletype/log) | Un archivo con extensión .log contiene la lista de texto sin formato con marca de tiempo. Por lo general, los softwares o sistemas operativos registran ciertos detalles de la actividad para ayudar a los desarrolladores o usuarios a rastrear lo que estaba sucediendo en un período de tiempo determinado. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/database/log) . |
| static readonly [Nsf](../../groupdocs.conversion.filetypes/databasefiletype/nsf) | Un archivo con extensión .nsf (Notes Storage Facility) es un formato de archivo de base de datos utilizado por el software IBM Notes, que anteriormente se conocía como Lotus Notes. Define el esquema para almacenar diferentes tipos de objetos, como correos electrónicos, citas, documentos, formularios y vistas. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/database/nsf) . |
| static readonly [Sql](../../groupdocs.conversion.filetypes/databasefiletype/sql) | Un archivo con extensión .sql es un archivo de lenguaje de consulta estructurado (SQL) que contiene código para trabajar con bases de datos relacionales. Se utiliza para escribir sentencias SQL para operaciones CRUD (Crear, Leer, Actualizar y Eliminar) en bases de datos. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/database/sql) . |

### Ver también

* class [FileType](../filetype)
* espacio de nombres [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* asamblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->