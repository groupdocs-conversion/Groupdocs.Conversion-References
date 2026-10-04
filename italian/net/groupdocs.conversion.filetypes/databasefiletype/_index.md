---
title: "DatabaseFileType"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Definisce documenti di database. Include i seguenti tipi di file Nsf./databasefiletype/nsfLog./databasefiletype/logSql./databasefiletype/sql"
type: docs
weight: 1090
url: /it/net/groupdocs.conversion.filetypes/databasefiletype/
---
## DatabaseFileType class

Definisce documenti di database. Include i seguenti tipi di file: [`Nsf`](./nsf)[`Log`](./log)[`Sql`](./sql)

```csharp
public sealed class DatabaseFileType : FileType
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [DatabaseFileType](databasefiletype)() | Costruttore di serializzazione |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Descrizione del tipo di file |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | L'estensione del file |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | La famiglia del file |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Il formato del file |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Confronta l'oggetto corrente con un altro. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Implementa [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Funziona come funzione hash predefinita. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Rappresentazione stringa |

## Campi

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| static readonly [Log](../../groupdocs.conversion.filetypes/databasefiletype/log) | Un file con estensione .log contiene un elenco di testo semplice con timestamp. Di solito, i dettagli di alcune attività sono registrati dal software o dai sistemi operativi per aiutare gli sviluppatori o gli utenti a tracciare cosa è accaduto in un determinato periodo di tempo. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/database/log). |
| static readonly [Nsf](../../groupdocs.conversion.filetypes/databasefiletype/nsf) | Un file con estensione .nsf (Notes Storage Facility) è un formato di file di database utilizzato dal software IBM Notes, precedentemente noto come Lotus Notes. Definisce lo schema per memorizzare diversi tipi di oggetti come email, appuntamenti, documenti, moduli e visualizzazioni. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/database/nsf). |
| static readonly [Sql](../../groupdocs.conversion.filetypes/databasefiletype/sql) | Un file con estensione .sql è un file Structured Query Language (SQL) che contiene codice per lavorare con database relazionali. Viene utilizzato per scrivere istruzioni SQL per operazioni CRUD (Create, Read, Update, Delete) sui database. Scopri di più su questo formato di file [qui](https://docs.fileformat.com/database/sql). |

### IConversionConvertOptions

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
