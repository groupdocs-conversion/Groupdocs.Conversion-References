---
title: "ProjectManagementFileType"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Define formatos de archivo de proyecto que son creados por software de gestión de proyectos como Microsoft Project, Primavera P6, etc."
type: docs
weight: 23
url: /es/java/com.groupdocs.conversion.filetypes/projectmanagementfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class ProjectManagementFileType extends FileType
```

Define formatos de archivo de proyecto que son creados por software de gestión de proyectos como Microsoft Project, Primavera P6, etc. Un archivo de proyecto es una colección de tareas, recursos y su programación para obtener un resultado medible en forma de producto o servicio.
Documentos de gestión de proyectos. Incluye los siguientes tipos de archivo:
[Mpp](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpp),
[Mpt](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpt),
[Mpx](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpx).
Aprende más sobre los formatos de gestión de proyectos [aquí](../https://wiki.fileformat.com/project-management).

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [ProjectManagementFileType()](#ProjectManagementFileType--) | Constructor de serialización |
|
## Campos

| Campo | Descripción |
| --- | --- |
|  | [Mpt](#Mpt) | Los archivos de plantilla de Microsoft Project contienen información básica y estructura junto con la configuración de documentos para crear archivos .MPP. |
|
|  | [Mpp](#Mpp) | MPP es un archivo de datos de Microsoft Project que almacena información relacionada con la gestión de proyectos de manera integrada. |
|
|  | [Mpx](#Mpx) | Microsoft Exchange File Format es un formato de archivo ASCII para la transferencia de información de proyectos entre Microsoft Project (MSP) y otras aplicaciones que soportan el formato de archivo MPX, como Primavera Project Planner, Sciforma y Timerline Precision Estimating. |
|
|  | [Xer](#Xer) | El formato de archivo XER es un formato de archivo de proyecto propietario utilizado por la aplicación de planificación y gestión de proyectos Primavera P6. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### ProjectManagementFileType() {#ProjectManagementFileType--}
```
public ProjectManagementFileType()
```


Constructor de serialización


### Mpt {#Mpt}
```
public static final ProjectManagementFileType Mpt
```


Los archivos de plantilla de Microsoft Project contienen información básica y estructura junto con la configuración de documentos para crear archivos .MPP.
Aprende más sobre este formato de archivo [aquí](../https://wiki.fileformat.com/project-management/mpt).


### Mpp {#Mpp}
```
public static final ProjectManagementFileType Mpp
```


MPP es un archivo de datos de Microsoft Project que almacena información relacionada con la gestión de proyectos de manera integrada.
Aprende más sobre este formato de archivo [aquí](../https://wiki.fileformat.com/project-management/mpp).


### Mpx {#Mpx}
```
public static final ProjectManagementFileType Mpx
```


Microsoft Exchange File Format es un formato de archivo ASCII para la transferencia de información de proyectos entre Microsoft Project (MSP) y otras aplicaciones que soportan el formato de archivo MPX, como Primavera Project Planner, Sciforma y Timerline Precision Estimating.
Aprende más sobre este formato de archivo [aquí](../https://wiki.fileformat.com/project-management/mpx).


### Xer {#Xer}
```
public static final ProjectManagementFileType Xer
```


El formato de archivo XER es un formato de archivo de proyecto propietario utilizado por la aplicación de planificación y gestión de proyectos Primavera P6.
Aprende más sobre este formato de archivo [aquí](../https://docs.fileformat.com/project-management/xer).


### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Opciones de conversión predeterminadas preparadas para el tipo de archivo


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
