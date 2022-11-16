---
title: ProjectManagementFileType
second_title: Referencia de API de GroupDocs.Conversion para .NET
description: Define los formatos de archivo de proyecto creados por el software de gestión de proyectos como Microsoft Project Primavera P6 etc. Un archivo de proyecto es una colección de tareas recursos y su programación para obtener un resultado medible en forma de producto o servicio. Documentos de gestión de proyectos. Incluye los siguientes tipos de archivo Mpp./projectmanagementfiletype/mpp  Mpt./projectmanagementfiletype/mpt  Mpx./projectmanagementfiletype/mpx . Obtenga más información sobre los formatos de gestión de proyectosaquíhttps//wiki.fileformat.com/projectmanagement .
type: docs
weight: 920
url: /es/net/groupdocs.conversion.filetypes/projectmanagementfiletype/
---
## ProjectManagementFileType class

Define los formatos de archivo de proyecto creados por el software de gestión de proyectos, como Microsoft Project, Primavera P6, etc. Un archivo de proyecto es una colección de tareas, recursos y su programación para obtener un resultado medible en forma de producto o servicio. Documentos de gestión de proyectos. Incluye los siguientes tipos de archivo: [`Mpp`](./mpp) , [`Mpt`](./mpt) , [`Mpx`](./mpx) . Obtenga más información sobre los formatos de gestión de proyectos[aquí](https://wiki.fileformat.com/project-management) .

```csharp
public sealed class ProjectManagementFileType : FileType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ProjectManagementFileType](projectmanagementfiletype)() | Constructor de serialización |

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
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | Determina si dos instancias de objeto son iguales. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina si dos instancias de objeto son iguales. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Sirve como la función hash predeterminada. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Representación de cadena |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Mpp](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpp) | MPP es un archivo de datos de Microsoft Project que almacena información relacionada con la gestión de proyectos de forma integrada. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/project-management/mpp) . |
| static readonly [Mpt](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpt) | Los archivos de plantilla de Microsoft Project contienen información y estructura básicas junto con la configuración del documento para crear archivos .MPP. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/project-management/mpt) . |
| static readonly [Mpx](../../groupdocs.conversion.filetypes/projectmanagementfiletype/mpx) | Microsoft Exchange File Format, es un formato de archivo ASCII para la transferencia de información de proyectos entre Microsoft Project (MSP) y otras aplicaciones compatibles con el formato de archivo MPX, como Primavera Project Planner, Sciforma y Timerline Precision Estimating. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/project-management/mpx) . |
| static readonly [Xer](../../groupdocs.conversion.filetypes/projectmanagementfiletype/xer) | El formato de archivo XER es un formato de archivo de proyecto propietario utilizado por la aplicación de gestión y planificación de proyectos Primavera P6. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/project-management/xer) . |

### Ver también

* class [FileType](../filetype)
* espacio de nombres [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* asamblea [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->