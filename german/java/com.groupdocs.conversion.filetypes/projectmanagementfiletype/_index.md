---
title: "ProjectManagementFileType"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Definiert Projektdateiformate, die von Projektmanagement-Software wie Microsoft Project, Primavera P6 usw. erstellt werden."
type: docs
weight: 23
url: /de/java/com.groupdocs.conversion.filetypes/projectmanagementfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)
```
public final class ProjectManagementFileType extends FileType
```

Definiert Projektdateiformate, die von Projektmanagement-Software wie Microsoft Project, Primavera P6 usw. erstellt werden. Eine Projektdatei ist eine Sammlung von Aufgaben, Ressourcen und deren Zeitplanung, um ein messbares Ergebnis in Form eines Produkts oder einer Dienstleistung zu erzielen.
Projektmanagement-Dokumente. Enthält die folgenden Dateitypen:
[Mpp](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpp),
[Mpt](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpt),
[Mpx](../../com.groupdocs.conversion.filetypes/projectmanagementfiletype#Mpx).
Erfahren Sie mehr über Projektmanagement-Formate [hier](../https://wiki.fileformat.com/project-management).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [ProjectManagementFileType()](#ProjectManagementFileType--) | Serialisierungskonstruktor |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Mpt](#Mpt) | Microsoft Project-Vorlagendateien enthalten grundlegende Informationen und Strukturen sowie Dokumenteneinstellungen zum Erstellen von .MPP-Dateien. |
|
|  | [Mpp](#Mpp) | MPP ist eine Microsoft Project-Datendatei, die Informationen zum Projektmanagement in integrierter Form speichert. |
|
|  | [Mpx](#Mpx) | Microsoft Exchange File Format ist ein ASCII-Dateiformat zum Übertragen von Projektinformationen zwischen Microsoft Project (MSP) und anderen Anwendungen, die das MPX-Dateiformat unterstützen, wie Primavera Project Planner, Sciforma und Timerline Precision Estimating. |
|
|  | [Xer](#Xer) | Das XER-Dateiformat ist ein proprietäres Projektdateiformat, das von der Primavera P6 Projektplanungs- und Managementanwendung verwendet wird. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### ProjectManagementFileType() {#ProjectManagementFileType--}
```
public ProjectManagementFileType()
```


Serialisierungskonstruktor


### Mpt {#Mpt}
```
public static final ProjectManagementFileType Mpt
```


Microsoft Project-Vorlagendateien enthalten grundlegende Informationen und Strukturen sowie Dokumenteneinstellungen zum Erstellen von .MPP-Dateien.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/project-management/mpt).


### Mpp {#Mpp}
```
public static final ProjectManagementFileType Mpp
```


MPP ist eine Microsoft Project-Datendatei, die Informationen zum Projektmanagement in integrierter Form speichert.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/project-management/mpp).


### Mpx {#Mpx}
```
public static final ProjectManagementFileType Mpx
```


Microsoft Exchange File Format ist ein ASCII-Dateiformat zum Übertragen von Projektinformationen zwischen Microsoft Project (MSP) und anderen Anwendungen, die das MPX-Dateiformat unterstützen, wie Primavera Project Planner, Sciforma und Timerline Precision Estimating.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://wiki.fileformat.com/project-management/mpx).


### Xer {#Xer}
```
public static final ProjectManagementFileType Xer
```


Das XER-Dateiformat ist ein proprietäres Projektdateiformat, das von der Primavera P6 Projektplanungs- und Managementanwendung verwendet wird.
Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/project-management/xer).


### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Standard‑Konvertierungsoptionen für den Dateityp vorbereitet


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
