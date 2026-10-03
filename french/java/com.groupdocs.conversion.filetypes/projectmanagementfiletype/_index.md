---
title: "ProjectManagementFileType"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Définit les formats de fichiers de projet créés par les logiciels de gestion de projet tels que Microsoft Project, Primavera P6, etc."
type: docs
weight: 23
url: /fr/java/com.groupdocs.conversion.filetypes/projectmanagementfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class ProjectManagementFileType extends FileType
```

Définit les formats de fichiers de projet créés par les logiciels de gestion de projet tels que Microsoft Project, Primavera P6, etc. Un fichier de projet est un ensemble de tâches, de ressources et de leur planification afin d'obtenir un résultat mesurable sous forme de produit ou de service.
Documents de gestion de projet. Inclut les types de fichiers suivants :
[Mpp](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpp),
[Mpt](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpt),
[Mpx](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpx).
En savoir plus sur les formats de gestion de projet [ici](../https://wiki.fileformat.com/project-management).

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [ProjectManagementFileType()](#ProjectManagementFileType--) | Constructeur de sérialisation |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [Mpt](#Mpt) | Les fichiers de modèle Microsoft Project contiennent des informations de base et une structure ainsi que les paramètres de document pour créer des fichiers .MPP. |
|
|  | [Mpp](#Mpp) | MPP est un fichier de données Microsoft Project qui stocke les informations liées à la gestion de projet de manière intégrée. |
|
|  | [Mpx](#Mpx) | Microsoft Exchange File Format est un format de fichier ASCII destiné au transfert d'informations de projet entre Microsoft Project (MSP) et d'autres applications qui prennent en charge le format de fichier MPX, telles que Primavera Project Planner, Sciforma et Timerline Precision Estimating. |
|
|  | [Xer](#Xer) | Le format de fichier XER est un format de fichier propriétaire utilisé par l'application de planification et de gestion de projet Primavera P6. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### ProjectManagementFileType() {#ProjectManagementFileType--}
```
public ProjectManagementFileType()
```


Constructeur de sérialisation


### Mpt {#Mpt}
```
public static final ProjectManagementFileType Mpt
```


Les fichiers de modèle Microsoft Project contiennent des informations de base et une structure ainsi que les paramètres de document pour créer des fichiers .MPP.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/project-management/mpt).


### Mpp {#Mpp}
```
public static final ProjectManagementFileType Mpp
```


MPP est un fichier de données Microsoft Project qui stocke les informations liées à la gestion de projet de manière intégrée.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/project-management/mpp).


### Mpx {#Mpx}
```
public static final ProjectManagementFileType Mpx
```


Microsoft Exchange File Format est un format de fichier ASCII destiné au transfert d'informations de projet entre Microsoft Project (MSP) et d'autres applications qui prennent en charge le format de fichier MPX, telles que Primavera Project Planner, Sciforma et Timerline Precision Estimating.
En savoir plus sur ce format de fichier [ici](../https://wiki.fileformat.com/project-management/mpx).


### Xer {#Xer}
```
public static final ProjectManagementFileType Xer
```


Le format de fichier XER est un format de fichier propriétaire utilisé par l'application de planification et de gestion de projet Primavera P6.
En savoir plus sur ce format de fichier [ici](../https://docs.fileformat.com/project-management/xer).


### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Options de conversion par défaut préparées pour le type de fichier


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
