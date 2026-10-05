---
title: "DatabaseFileType"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Define documentos CAD (Computer Aided Design) que se utilizan para formatos de archivo de gráficos 3D y pueden contener diseños 2D o 3D. Incluye los siguientes tipos: [Dgn](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Dgn), [Dwf](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Dwf), [Dwg](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Dwg), [Dwt](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Dwt), [Dxf](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Dxf), [Ifc](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Ifc), [Igs](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Igs), [Plt](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Plt), [Stl](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Stl). [Cf2](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Cf2). [Dwfx](../../com.groupdocs.conversion.filetypes/cadfiletype\\#Dwfx). Obtenga más información sobre los formatos CAD [here][]."
type: docs
weight: 12
url: /es/nodejs-java/com.groupdocs.conversion.filetypes/databasefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DatabaseFileType extends FileType implements Serializable
```

Define documentos CAD (Diseño Asistido por Computadora) que se utilizan para formatos de archivo de gráficos 3D y pueden contener diseños 2D o 3D. Incluye los siguientes tipos: [Nsf](../../com.groupdocs.conversion.filetypes/databasefiletype\#Nsf), [Log](../../com.groupdocs.conversion.filetypes/databasefiletype\#Log), [Sql](../../com.groupdocs.conversion.filetypes/databasefiletype\#Sql), Obtenga más información sobre los formatos CAD [aquí][].


[here]: https://wiki.fileformat.com/cad
## Constructores

| Constructor | Descripción |
| --- | --- |
| [DatabaseFileType()](#DatabaseFileType--) | Constructor de serialización |
## Campos

| Campo | Descripción |
| --- | --- |
| [Nsf](#Nsf) | Un archivo con extensión .nsf (Notes Storage Facility) es un formato de archivo de base de datos utilizado por el software IBM Notes, que anteriormente se conocía como Lotus Notes. |
| [Log](#Log) | Un archivo con extensión .log contiene una lista de texto plano con marca de tiempo. |
| [Sql](#Sql) | Un archivo con extensión .sql es un archivo Structured Query Language (SQL) que contiene código para trabajar con bases de datos relacionales. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### DatabaseFileType() {#DatabaseFileType--}
```
public DatabaseFileType()
```


Constructor de serialización

### Nsf {#Nsf}
```
public static final DatabaseFileType Nsf
```


Un archivo con extensión .nsf (Notes Storage Facility) es un formato de archivo de base de datos utilizado por el software IBM Notes, que anteriormente se conocía como Lotus Notes. Define el esquema para almacenar diferentes tipos de objetos como correos electrónicos, citas, documentos, formularios y vistas. Obtenga más información sobre este formato de archivo [aquí][].


[here]: https://docs.fileformat.com/database/nsf

### Log {#Log}
```
public static final DatabaseFileType Log
```


Un archivo con extensión .log contiene una lista de texto plano con marca de tiempo. Normalmente, ciertos detalles de actividad son registrados por los programas o sistemas operativos para ayudar a los desarrolladores o usuarios a rastrear lo que sucedía en un período de tiempo determinado. Obtén más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/database/log

### Sql {#Sql}
```
public static final DatabaseFileType Sql
```


Un archivo con extensión .sql es un archivo Structured Query Language (SQL) que contiene código para trabajar con bases de datos relacionales. Se utiliza para escribir sentencias SQL para operaciones CRUD (Crear, Leer, Actualizar y Eliminar) en bases de datos. Obtén más información sobre este formato de archivo [here][].


[here]: https://docs.fileformat.com/database/sql

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opciones de carga predeterminadas preparadas para el tipo de archivo de origen

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
