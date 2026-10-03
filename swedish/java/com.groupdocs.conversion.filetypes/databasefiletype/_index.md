---
title: "DatabaseFileType"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Definierar CAD‑dokument (Computer Aided Design) som används för 3D‑grafikfilformat och kan innehålla 2D‑ eller 3D‑designer."
type: docs
weight: 12
url: /sv/java/com.groupdocs.conversion.filetypes/databasefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DatabaseFileType extends FileType implements Serializable
```

Definierar CAD-dokument (Computer Aided Design) som används för 3D-grafikfilformat och kan innehålla 2D- eller 3D-design.
Inkluderar följande typer:
[Nsf](../../com.groupdocs.conversion.filetypes/databasefiletype#Nsf),
[Log](../../com.groupdocs.conversion.filetypes/databasefiletype#Log),
[Sql](../../com.groupdocs.conversion.filetypes/databasefiletype#Sql),
Läs mer om CAD‑format [här](../https://wiki.fileformat.com/cad).

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [DatabaseFileType()](#DatabaseFileType--) | Serialiseringskonstruktor |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Nsf](#Nsf) | En fil med .nsf‑tillägg (Notes Storage Facility) är ett databasfilformat som används av IBM Notes‑programvaran, som tidigare var känd som Lotus Notes. |
|
|  | [Log](#Log) | En fil med .log‑tillägg innehåller en lista med vanlig text och tidsstämpel. |
|
|  | [Sql](#Sql) | En fil med .sql‑tillägg är en Structured Query Language (SQL)-fil som innehåller kod för att arbeta med relationsdatabaser. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### DatabaseFileType() {#DatabaseFileType--}
```
public DatabaseFileType()
```


Serialiseringskonstruktor


### Nsf {#Nsf}
```
public static final DatabaseFileType Nsf
```


En fil med .nsf (Notes Storage Facility)-ändelse är ett databasfilformat som används av IBM Notes‑programvaran, som tidigare hette Lotus Notes. Den definierar schemat för att lagra olika typer av objekt som e‑post, möten, dokument, formulär och vyer. Läs mer om detta filformat [here](../https://docs.fileformat.com/database/nsf).


### Log {#Log}
```
public static final DatabaseFileType Log
```


En fil med .log‑ändelse innehåller en lista med vanlig text och tidsstämpel. Vanligtvis loggas viss aktivitetsdetalj av programvaror eller operativsystem för att hjälpa utvecklare eller användare att spåra vad som hände under en viss tidsperiod. Läs mer om detta filformat [here](../https://docs.fileformat.com/database/log).


### Sql {#Sql}
```
public static final DatabaseFileType Sql
```


En fil med .sql‑ändelse är en Structured Query Language (SQL)-fil som innehåller kod för att arbeta med relationsdatabaser. Den används för att skriva SQL‑satser för CRUD‑operationer (Create, Read, Update och Delete) på databaser. Läs mer om detta filformat [here](../https://docs.fileformat.com/database/sql).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Förberedda standardalternativ för inläsning för källfiltypen


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
