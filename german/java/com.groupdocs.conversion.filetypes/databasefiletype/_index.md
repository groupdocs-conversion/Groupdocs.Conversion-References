---
title: "DatabaseFileType"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Definiert CAD‑Dokumente (Computer Aided Design), die für 3D‑Grafikdateiformate verwendet werden und 2D‑ oder 3D‑Entwürfe enthalten können."
type: docs
weight: 12
url: /de/java/com.groupdocs.conversion.filetypes/databasefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DatabaseFileType extends FileType implements Serializable
```

Definiert CAD-Dokumente (Computer Aided Design), die für 3D‑Grafikdateiformate verwendet werden und 2D‑ oder 3D‑Designs enthalten können.
Enthält die folgenden Typen:
[Nsf](../../com.groupdocs.conversion.filetypes/databasefiletype#Nsf),
[Log](../../com.groupdocs.conversion.filetypes/databasefiletype#Log),
[Sql](../../com.groupdocs.conversion.filetypes/databasefiletype#Sql),
Erfahren Sie mehr über CAD‑Formate [hier](../https://wiki.fileformat.com/cad).

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [DatabaseFileType()](#DatabaseFileType--) | Serialisierungskonstruktor |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Nsf](#Nsf) | Eine Datei mit der Erweiterung .nsf (Notes Storage Facility) ist ein Datenbankdateiformat, das von der IBM‑Notes‑Software verwendet wird, die zuvor als Lotus Notes bekannt war. |
|
|  | [Log](#Log) | Eine Datei mit der Erweiterung .log enthält eine Liste von Klartext mit Zeitstempel. |
|
|  | [Sql](#Sql) | Eine Datei mit der Erweiterung .sql ist eine Structured Query Language (SQL)‑Datei, die Code zur Arbeit mit relationalen Datenbanken enthält. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### DatabaseFileType() {#DatabaseFileType--}
```
public DatabaseFileType()
```


Serialisierungskonstruktor


### Nsf {#Nsf}
```
public static final DatabaseFileType Nsf
```


Eine Datei mit der Erweiterung .nsf (Notes Storage Facility) ist ein Datenbankdateiformat, das von der IBM‑Notes‑Software verwendet wird, die zuvor als Lotus Notes bekannt war. Sie definiert das Schema zum Speichern verschiedener Objektarten wie E‑Mails, Termine, Dokumente, Formulare und Ansichten. Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/database/nsf).


### Log {#Log}
```
public static final DatabaseFileType Log
```


Eine Datei mit der Erweiterung .log enthält eine Liste von Klartext mit Zeitstempel. In der Regel werden bestimmte Aktivitätsdetails von Software oder Betriebssystemen protokolliert, um Entwicklern oder Benutzern zu helfen, nachzuvollziehen, was in einem bestimmten Zeitraum passiert ist. Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/database/log).


### Sql {#Sql}
```
public static final DatabaseFileType Sql
```


Eine Datei mit der Erweiterung .sql ist eine Structured Query Language (SQL)‑Datei, die Code zur Arbeit mit relationalen Datenbanken enthält. Sie wird verwendet, um SQL‑Anweisungen für CRUD‑ (Create, Read, Update und Delete) Vorgänge auf Datenbanken zu schreiben. Erfahren Sie mehr über dieses Dateiformat [hier](../https://docs.fileformat.com/database/sql).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Standard‑Ladeoptionen für den Quelldateityp vorbereitet


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
