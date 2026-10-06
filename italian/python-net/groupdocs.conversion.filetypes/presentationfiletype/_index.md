---
title: "Classe PresentationFileType"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Rappresenta formati di file di presentazione che memorizzano una raccolta di record per gestire dati di presentazione come diapositive, forme, testo, animazioni, video, audio e oggetti incorporati."
type: docs
url: /it/python-net/groupdocs.conversion.filetypes/presentationfiletype/
is_root: false
weight: 160
---


## PresentationFileType class

Rappresenta formati di file di presentazione che memorizzano una raccolta di record per gestire dati di presentazione come diapositive, forme, testo, animazioni, video, audio e oggetti incorporati.

Include i seguenti tipi di file:
- [`PresentationFileType.odp`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/odp/)
- [`PresentationFileType.otp`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/otp/)
- [`PresentationFileType.pot`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pot/)
- [`PresentationFileType.potm`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/potm/)
- [`PresentationFileType.potx`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/potx/)
- [`PresentationFileType.pps`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pps/)
- [`PresentationFileType.ppsm`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppsm/)
- [`PresentationFileType.ppsx`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppsx/)
- [`PresentationFileType.ppt`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppt/)
- [`PresentationFileType.pptm`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pptm/)
- [`PresentationFileType.pptx`](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pptx/).

Scopri di più sui formati di presentazione su https://wiki.fileformat.com/presentation.

Il tipo PresentationFileType espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/__init__/) | Inizializza un PresentationFileType per la serializzazione. |

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
| [PPT](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppt/) | Un file con estensione PPT rappresenta un file PowerPoint che consiste in una raccolta di diapositive per la visualizzazione come SlideShow. Specifica il Binary File Format utilizzato da Microsoft PowerPoint 97-2003. Scopri di più su questo formato di file qui. |
| [PPS](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pps/) | PPS, PowerPoint Slide Show, i file sono creati utilizzando Microsoft PowerPoint per scopi di Slide Show. La lettura e la creazione di file PPS è supportata da Microsoft PowerPoint 97-2003. Scopri di più su questo formato di file qui. |
| [PPTX](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pptx/) | I file con estensione PPTX sono file di presentazione creati con la popolare applicazione Microsoft PowerPoint. A differenza della versione precedente del formato di file di presentazione PPT, che era binario, il formato PPTX si basa sul Microsoft PowerPoint open XML presentation file format. Scopri di più su questo formato di file qui. |
| [PPSX](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppsx/) | PPSX, Power Point Slide Show, i file sono creati utilizzando Microsoft PowerPoint 2007 e versioni successive per scopi di Slide Show. Scopri di più su questo formato di file qui. |
| [ODP](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/odp/) | I file con estensione ODP rappresentano il formato di file di presentazione utilizzato da OpenOffice.org nello standard OASISOpen. Scopri di più su questo formato di file qui. |
| [OTP](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/otp/) | I file con estensione .OTP rappresentano file modello di presentazione creati dalle applicazioni nel formato standard OASIS OpenDocument. Scopri di più su questo formato di file qui. |
| [POTX](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/potx/) | I file con estensione .POTX rappresentano presentazioni modello di Microsoft PowerPoint create con Microsoft PowerPoint 2007 e versioni successive. Scopri di più su questo formato di file qui. |
| [POT](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pot/) | I file con estensione .POT rappresentano file modello di Microsoft PowerPoint creati dalle versioni PowerPoint 97-2003. Scopri di più su questo formato di file qui. |
| [POTM](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/potm/) | I file con estensione POTM sono file modello di Microsoft PowerPoint con supporto per macro. I file POTM sono creati con PowerPoint 2007 o versioni successive e contengono impostazioni predefinite che possono essere usate per creare ulteriori file di presentazione. Scopri di più su questo formato di file qui. |
| [PPTM](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/pptm/) | I file con estensione PPTM sono file di presentazione con macro abilitati, creati con Microsoft PowerPoint 2007 o versioni successive. Scopri di più su questo formato di file qui. |
| [PPSM](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/ppsm/) | I file con estensione PPSM rappresentano il formato di file Slide Show con macro abilitati, creati con Microsoft PowerPoint 2007 o versioni successive. Scopri di più su questo formato di file qui. |
| [FODP](/conversion/python-net/groupdocs.conversion.filetypes/presentationfiletype/fodp/) | I file con estensione FODP rappresentano una Presentazione OpenDocument Flat XML. Il file di presentazione è salvato nel formato OpenDocument, ma utilizzando un formato XML flat invece del contenitore .ZIP usato dai file .ODP standard. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Tipo di file sconosciuto (eredita da [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Vedi anche
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
