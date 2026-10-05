---
title: "DatabaseFileType"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Definieert CAD‑documenten (Computer Aided Design) die worden gebruikt voor 3D‑grafische bestandsformaten en 2D‑ of 3D‑ontwerpen kunnen bevatten."
type: docs
weight: 12
url: /nl/nodejs-java/com.groupdocs.conversion.filetypes/databasefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DatabaseFileType extends FileType implements Serializable
```

Definieert CAD‑documenten (Computer Aided Design) die worden gebruikt voor 3D‑grafische bestandsformaten en kunnen 2D‑ of 3D‑ontwerpen bevatten. Bevat de volgende typen: [Nsf](../../com.groupdocs.conversion.filetypes/databasefiletype\#Nsf), [Log](../../com.groupdocs.conversion.filetypes/databasefiletype\#Log), [Sql](../../com.groupdocs.conversion.filetypes/databasefiletype\#Sql), Meer informatie over CAD‑formaten [hier][].


[here]: https://wiki.fileformat.com/cad
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [DatabaseFileType()](#DatabaseFileType--) | Serialisatieconstructor |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Nsf](#Nsf) | Een bestand met de extensie .nsf (Notes Storage Facility) is een database‑bestandsformaat dat wordt gebruikt door de IBM Notes‑software, die voorheen bekend stond als Lotus Notes. |
| [Log](#Log) | Een bestand met de extensie .log bevat een lijst van platte tekst met tijdstempel. |
| [Sql](#Sql) | Een bestand met de extensie .sql is een Structured Query Language (SQL)‑bestand dat code bevat om met relationele databases te werken. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### DatabaseFileType() {#DatabaseFileType--}
```
public DatabaseFileType()
```


Serialisatieconstructor

### Nsf {#Nsf}
```
public static final DatabaseFileType Nsf
```


Een bestand met de extensie .nsf (Notes Storage Facility) is een database‑bestandsformaat dat wordt gebruikt door de IBM Notes‑software, die voorheen bekend stond als Lotus Notes. Het definieert het schema om verschillende soorten objecten op te slaan, zoals e‑mails, afspraken, documenten, formulieren en weergaven. Meer informatie over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/database/nsf

### Log {#Log}
```
public static final DatabaseFileType Log
```


Een bestand met .log-extensie bevat een lijst met platte tekst met tijdstempel. Gewoonlijk wordt bepaalde activiteitsdetail vastgelegd door de software of besturingssystemen om ontwikkelaars of gebruikers te helpen bij het volgen van wat er gebeurde gedurende een bepaalde tijdsperiode. Leer meer over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/database/log

### Sql {#Sql}
```
public static final DatabaseFileType Sql
```


Een bestand met .sql-extensie is een Structured Query Language (SQL)-bestand dat code bevat om met relationele databases te werken. Het wordt gebruikt om SQL‑instructies te schrijven voor CRUD (Create, Read, Update, and Delete)-bewerkingen op databases. Leer meer over dit bestandsformaat [hier][].


[here]: https://docs.fileformat.com/database/sql

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Voorbereide standaard laadopties voor het bronbestandstype

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
