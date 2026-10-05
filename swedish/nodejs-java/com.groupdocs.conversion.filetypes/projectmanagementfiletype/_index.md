---
title: "ProjectManagementFileType"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Definierar projektfilformat som skapas av projektledningsprogramvara såsom Microsoft Project, Primavera P6 osv."
type: docs
weight: 23
url: /sv/nodejs-java/com.groupdocs.conversion.filetypes/projectmanagementfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class ProjectManagementFileType extends FileType
```

Definierar projektfilformat som skapas av projektledningsprogramvara såsom Microsoft Project, Primavera P6 etc. En projektfil är en samling av uppgifter, resurser och deras schemaläggning för att få ett mätbart resultat i form av en produkt eller en tjänst. Projektledningsdokument. Inkluderar följande filtyper: [Mpp](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype\#Mpp), [Mpt](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype\#Mpt), [Mpx](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype\#Mpx). Läs mer om projektledningsformat [här][].


[here]: https://wiki.fileformat.com/project-management
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ProjectManagementFileType()](#ProjectManagementFileType--) | Serialiseringskonstruktor |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Mpt](#Mpt) | Microsoft Project-mallfiler innehåller grundläggande information och struktur samt dokumentinställningar för att skapa .MPP-filer. |
| [Mpp](#Mpp) | MPP är en Microsoft Project-datafil som lagrar information relaterad till projektledning på ett integrerat sätt. |
| [Mpx](#Mpx) | Microsoft Exchange File Format är ett ASCII-filformat för överföring av projektinformation mellan Microsoft Project (MSP) och andra applikationer som stöder MPX-filformatet, såsom Primavera Project Planner, Sciforma och Timerline Precision Estimating. |
| [Xer](#Xer) | XER-filformatet är ett proprietärt projektfilformat som används av Primavera P6:s projektplanerings- och hanteringsapplikation. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### ProjectManagementFileType() {#ProjectManagementFileType--}
```
public ProjectManagementFileType()
```


Serialiseringskonstruktor

### Mpt {#Mpt}
```
public static final ProjectManagementFileType Mpt
```


Microsoft Project-mallfiler innehåller grundläggande information och struktur samt dokumentinställningar för att skapa .MPP-filer. Läs mer om detta filformat [här][].


[here]: https://wiki.fileformat.com/project-management/mpt

### Mpp {#Mpp}
```
public static final ProjectManagementFileType Mpp
```


MPP är en Microsoft Project-datafil som lagrar information relaterad till projektledning på ett integrerat sätt. Läs mer om detta filformat [här][].


[here]: https://wiki.fileformat.com/project-management/mpp

### Mpx {#Mpx}
```
public static final ProjectManagementFileType Mpx
```


Microsoft Exchange File Format är ett ASCII-filformat för överföring av projektinformation mellan Microsoft Project (MSP) och andra applikationer som stöder MPX-filformatet, såsom Primavera Project Planner, Sciforma och Timerline Precision Estimating. Läs mer om detta filformat [här][].


[here]: https://wiki.fileformat.com/project-management/mpx

### Xer {#Xer}
```
public static final ProjectManagementFileType Xer
```


XER-filformatet är ett proprietärt projektfilformat som används av Primavera P6:s projektplanerings- och hanteringsapplikation. Läs mer om detta filformat [här][].


[here]: https://docs.fileformat.com/project-management/xer

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Förberedda standardalternativ för konvertering för filtypen

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
