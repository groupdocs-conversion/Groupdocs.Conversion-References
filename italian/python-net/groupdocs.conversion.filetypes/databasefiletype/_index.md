---
title: "Classe DatabaseFileType"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Definisce i documenti del database."
type: docs
url: /it/python-net/groupdocs.conversion.filetypes/databasefiletype/
is_root: false
weight: 40
---


## DatabaseFileType class

Definisce i documenti di database. Include i seguenti tipi di file.

- [`DatabaseFileType.nsf`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/nsf/)
- [`DatabaseFileType.log`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/log/)
- [`DatabaseFileType.sql`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/sql/)

Il tipo DatabaseFileType espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/__init__/) | Inizializza un nuovo DatabaseFileType per la serializzazione. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | Confronta l'oggetto corrente con un altro. (eredita da [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | (eredita da [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | Implementa il confronto di uguaglianza definito da [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/). (ereditato da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | (eredita da [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | (eredita da [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | Ottiene il FileType per l'estensione di file fornita. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | Restituisce il FileType per il file_name specificato. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | Restituisce il FileType per lo stream di documento fornito. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | (eredita da [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | Fornisce la funzione hash predefinita. (eredita da [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | Rappresentazione stringa del tipo di file. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | La descrizione del tipo di file. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | L'estensione del file. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | La famiglia del file. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | Il formato del file. (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Campi
| Campo | Descrizione |
| :- | :- |
| [NSF](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/nsf/) | Un file con estensione .nsf (Notes Storage Facility) è un formato di file di database utilizzato dal software IBM Notes, precedentemente noto come Lotus Notes. Definisce lo schema per memorizzare diversi tipi di oggetti come email, appuntamenti, documenti, moduli e viste. Scopri di più su questo formato file qui. |
| [LOG](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/log/) | Un file con estensione .log contiene un elenco di testo semplice con timestamp. Di solito, alcuni dettagli di attività vengono registrati dai software o sistemi operativi per aiutare gli sviluppatori o gli utenti a tracciare cosa è accaduto in un determinato periodo di tempo. Scopri di più su questo formato file qui. |
| [SQL](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/sql/) | Un file con estensione .sql è un file Structured Query Language (SQL) che contiene codice per lavorare con database relazionali. Viene usato per scrivere istruzioni SQL per operazioni CRUD (Create, Read, Update, Delete) sui database. Scopri di più su questo formato file qui. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Tipo di file sconosciuto (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Vedi anche
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
