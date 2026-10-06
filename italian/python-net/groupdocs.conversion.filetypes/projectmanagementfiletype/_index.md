---
title: "classe ProjectManagementFileType"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Definisce i formati di file Project creati da software di gestione progetti come Microsoft Project, Primavera P6 ecc."
type: docs
url: /it/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/
is_root: false
weight: 170
---


## ProjectManagementFileType class

Definisce i formati di file Project creati da software di gestione progetti come Microsoft Project, Primavera P6 ecc.

Un file di progetto è una raccolta di attività, risorse e la loro pianificazione per ottenere un risultato misurabile sotto forma di prodotto o servizio. Documenti di gestione del progetto. Include i seguenti tipi di file: [`ProjectManagementFileType.mpp`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp/), [`ProjectManagementFileType.mpt`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt/), [`ProjectManagementFileType.mpx`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx/). Scopri di più sui formati di Project Management qui: https://wiki.fileformat.com/project-management.

Il tipo ProjectManagementFileType espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/__init__/) | Inizializza un ProjectManagementFileType per la serializzazione. |

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
| [MPT](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt/) | I file modello di Microsoft Project contengono informazioni di base e struttura insieme alle impostazioni del documento per creare file .MPP. Scopri di più su questo formato di file qui. |
| [MPP](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp/) | MPP è un file di dati Microsoft Project che memorizza informazioni relative alla gestione del progetto in modo integrato. Scopri di più su questo formato di file qui. |
| [MPX](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx/) | Microsoft Exchange File Format è un formato file ASCII per il trasferimento di informazioni di progetto tra Microsoft Project (MSP) e altre applicazioni che supportano il formato file MPX, come Primavera Project Planner, Sciforma e Timerline Precision Estimating. Scopri di più su questo formato di file qui. |
| [XER](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/xer/) | Il formato file XER è un formato file proprietario per progetti utilizzato dall'applicazione di pianificazione e gestione dei progetti Primavera P6. Scopri di più su questo formato di file qui. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Tipo di file sconosciuto (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Vedi anche
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
