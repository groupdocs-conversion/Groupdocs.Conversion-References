---
title: "ProjectManagementFileType"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Definieert projectbestandsformaten die worden gemaakt door projectmanagementsoftware zoals Microsoft Project, Primavera P6, enz."
type: docs
weight: 23
url: /nl/nodejs-java/com.groupdocs.conversion.filetypes/projectmanagementfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class ProjectManagementFileType extends FileType
```

Definieert projectbestandsformaten die worden gemaakt door projectmanagementsoftware zoals Microsoft Project, Primavera P6, enz. Een projectbestand is een verzameling van taken, resources en hun planning om een meetbaar resultaat te behalen in de vorm van een product of een dienst. Projectmanagementdocumenten. Bevat de volgende bestandstypen: [Mpp](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype\#Mpp), [Mpt](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype\#Mpt), [Mpx](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype\#Mpx). Leer meer over projectmanagementformaten [here][].


[here]: https://wiki.fileformat.com/project-management
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ProjectManagementFileType()](#ProjectManagementFileType--) | Serialisatieconstructor |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Mpt](#Mpt) | Microsoft Project-sjabloonbestanden bevatten basisinformatie en structuur, samen met documentinstellingen voor het maken van .MPP-bestanden. |
| [Mpp](#Mpp) | MPP is een Microsoft Project-gegevensbestand dat informatie met betrekking tot projectmanagement op een geïntegreerde manier opslaat. |
| [Mpx](#Mpx) | Microsoft Exchange File Format is een ASCII-bestandsformaat voor het overdragen van projectinformatie tussen Microsoft Project (MSP) en andere toepassingen die het MPX-bestandsformaat ondersteunen, zoals Primavera Project Planner, Sciforma en Timerline Precision Estimating. |
| [Xer](#Xer) | Het XER-bestandsformaat is een propriëtair projectbestandsformaat dat wordt gebruikt door de Primavera P6 projectplanning- en beheerapplicatie. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### ProjectManagementFileType() {#ProjectManagementFileType--}
```
public ProjectManagementFileType()
```


Serialisatieconstructor

### Mpt {#Mpt}
```
public static final ProjectManagementFileType Mpt
```


Microsoft Project-sjabloonbestanden bevatten basisinformatie en structuur, samen met documentinstellingen voor het maken van .MPP-bestanden. Leer meer over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/project-management/mpt

### Mpp {#Mpp}
```
public static final ProjectManagementFileType Mpp
```


MPP is een Microsoft Project-gegevensbestand dat informatie met betrekking tot projectmanagement op een geïntegreerde manier opslaat. Leer meer over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/project-management/mpp

### Mpx {#Mpx}
```
public static final ProjectManagementFileType Mpx
```


Microsoft Exchange File Format is een ASCII-bestandsformaat voor het overdragen van projectinformatie tussen Microsoft Project (MSP) en andere toepassingen die het MPX-bestandsformaat ondersteunen, zoals Primavera Project Planner, Sciforma en Timerline Precision Estimating. Leer meer over dit bestandsformaat [here][].


[here]: https://wiki.fileformat.com/project-management/mpx

### Xer {#Xer}
```
public static final ProjectManagementFileType Xer
```


Het XER-bestandsformaat is een propriëtair projectbestandsformaat dat wordt gebruikt door de Primavera P6 projectplanning- en beheerapplicatie. Leer meer over dit bestandsformaat [here][].


[here]: https://docs.fileformat.com/project-management/xer

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Voorbereide standaard conversie‑opties voor het bestandstype

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
