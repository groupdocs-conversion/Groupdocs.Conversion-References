---
title: "ProjectManagementFileType"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Definisce i formati di file di progetto creati da software di gestione progetti come Microsoft Project, Primavera P6, ecc."
type: docs
weight: 23
url: /it/java/com.groupdocs.conversion.filetypes/projectmanagementfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class ProjectManagementFileType extends FileType
```

Definisce i formati di file di progetto creati da software di gestione progetti come Microsoft Project, Primavera P6, ecc. Un file di progetto è una raccolta di attività, risorse e la loro pianificazione per ottenere un risultato misurabile sotto forma di prodotto o servizio.
Documenti di gestione progetti. Include i seguenti tipi di file:
[Mpp](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpp),
[Mpt](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpt),
[Mpx](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpx).
Scopri di più sui formati di gestione progetti [qui](../https://wiki.fileformat.com/project-management).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [ProjectManagementFileType()](#ProjectManagementFileType--) | Costruttore di serializzazione |
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Mpt](#Mpt) | I file modello di Microsoft Project contengono informazioni di base e struttura insieme alle impostazioni del documento per creare file .MPP. |
|
|  | [Mpp](#Mpp) | MPP è il file dati di Microsoft Project che memorizza le informazioni relative alla gestione del progetto in modo integrato. |
|
|  | [Mpx](#Mpx) | Microsoft Exchange File Format è un formato di file ASCII per il trasferimento di informazioni di progetto tra Microsoft Project (MSP) e altre applicazioni che supportano il formato file MPX, come Primavera Project Planner, Sciforma e Timerline Precision Estimating. |
|
|  | [Xer](#Xer) | Il formato di file XER è un formato di file di progetto proprietario utilizzato dall'applicazione di pianificazione e gestione progetti Primavera P6. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### ProjectManagementFileType() {#ProjectManagementFileType--}
```
public ProjectManagementFileType()
```


Costruttore di serializzazione


### Mpt {#Mpt}
```
public static final ProjectManagementFileType Mpt
```


I file modello di Microsoft Project contengono informazioni di base e struttura insieme alle impostazioni del documento per creare file .MPP.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/project-management/mpt).


### Mpp {#Mpp}
```
public static final ProjectManagementFileType Mpp
```


MPP è il file dati di Microsoft Project che memorizza le informazioni relative alla gestione del progetto in modo integrato.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/project-management/mpp).


### Mpx {#Mpx}
```
public static final ProjectManagementFileType Mpx
```


Microsoft Exchange File Format è un formato di file ASCII per il trasferimento di informazioni di progetto tra Microsoft Project (MSP) e altre applicazioni che supportano il formato file MPX, come Primavera Project Planner, Sciforma e Timerline Precision Estimating.
Scopri di più su questo formato di file [qui](../https://wiki.fileformat.com/project-management/mpx).


### Xer {#Xer}
```
public static final ProjectManagementFileType Xer
```


Il formato di file XER è un formato di file di progetto proprietario utilizzato dall'applicazione di pianificazione e gestione progetti Primavera P6.
Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/project-management/xer).


### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Opzioni di conversione predefinite preparate per il tipo di file


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
