---
title: "DatabaseFileType"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Definisce i documenti CAD (Computer Aided Design) che sono usati per formati di file grafici 3D e possono contenere progetti 2D o 3D."
type: docs
weight: 12
url: /it/java/com.groupdocs.conversion.filetypes/databasefiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class DatabaseFileType extends FileType implements Serializable
```

Definisce documenti CAD (Computer Aided Design) che sono utilizzati per formati di file grafici 3D e possono contenere progetti 2D o 3D.
Include i seguenti tipi:
[Nsf](../../com.groupdocs.conversion.filetypes/databasefiletype#Nsf),
[Log](../../com.groupdocs.conversion.filetypes/databasefiletype#Log),
[Sql](../../com.groupdocs.conversion.filetypes/databasefiletype#Sql),
Scopri di più sui formati CAD [qui](../https://wiki.fileformat.com/cad).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [DatabaseFileType()](#DatabaseFileType--) | Costruttore di serializzazione |
|
## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Nsf](#Nsf) | Un file con estensione .nsf (Notes Storage Facility) è un formato di file di database utilizzato dal software IBM Notes, precedentemente noto come Lotus Notes. |
|
|  | [Log](#Log) | Un file con estensione .log contiene un elenco di testo semplice con timestamp. |
|
|  | [Sql](#Sql) | Un file con estensione .sql è un file Structured Query Language (SQL) che contiene codice per lavorare con database relazionali. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
### DatabaseFileType() {#DatabaseFileType--}
```
public DatabaseFileType()
```


Costruttore di serializzazione


### Nsf {#Nsf}
```
public static final DatabaseFileType Nsf
```


Un file con estensione .nsf (Notes Storage Facility) è un formato di file di database utilizzato dal software IBM Notes, precedentemente noto come Lotus Notes. Definisce lo schema per memorizzare diversi tipi di oggetti come email, appuntamenti, documenti, moduli e visualizzazioni. Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/database/nsf).


### Log {#Log}
```
public static final DatabaseFileType Log
```


Un file con estensione .log contiene un elenco di testo semplice con timestamp. Di solito, i dettagli di alcune attività vengono registrati dai software o dai sistemi operativi per aiutare sviluppatori o utenti a tracciare cosa è accaduto in un determinato periodo di tempo. Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/database/log).


### Sql {#Sql}
```
public static final DatabaseFileType Sql
```


Un file con estensione .sql è un file Structured Query Language (SQL) che contiene codice per lavorare con database relazionali. Viene utilizzato per scrivere istruzioni SQL per operazioni CRUD (Create, Read, Update, Delete) sui database. Scopri di più su questo formato di file [qui](../https://docs.fileformat.com/database/sql).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opzioni di caricamento predefinite preparate per il tipo di file di origine


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
