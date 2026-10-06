---
title: "classe TxtLoadOptions"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Opzioni per il caricamento dei documenti Txt."
type: docs
url: /it/python-net/groupdocs.conversion.options.load/txtloadoptions/
is_root: false
weight: 500
---


## TxtLoadOptions class

Opzioni per il caricamento dei documenti Txt.

Configurazione dei font per testo semplice:

Poiché i file TXT non contengono informazioni sui font, usa DefaultTextFont per specificare il font per il rendering del contenuto di testo semplice durante la conversione.

Il tipo TxtLoadOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/__init__/) | Inizializza una nuova istanza di [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/). |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Determina se due istanze di oggetti sono uguali. (eredita da [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (eredita da [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (eredita da [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Funge da funzione hash predefinita. (eredita da [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/default_font/) | Il font da utilizzare durante il rendering del contenuto di testo semplice durante la conversione. Predefinito: Arial 10pt. |
| [detect_numbering_with_whitespaces](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/) | La proprietà specifica come gli elementi di elenco numerato vengono riconosciuti quando un documento di testo semplice viene convertito. Il valore predefinito è True. |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/encoding/) | La codifica utilizzata durante il caricamento di un documento Txt. Può essere None. Il valore predefinito è None. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/format/) | Il tipo di file del documento di input. |
| [leading_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/leading_spaces_options/) | L'opzione preferita per la gestione degli spazi iniziali. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/margin_settings/) | Le impostazioni dei margini, come definite da [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/). |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/size_settings/) | Le opzioni di dimensione della pagina per il caricamento di un documento TXT. |
| [trailing_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/trailing_spaces_options/) | L'opzione preferita per gestire gli spazi finali. Il valore predefinito è [`TxtTrailingSpacesOptions.trim`](/conversion/python-net/groupdocs.conversion.options.load/txttrailingspacesoptions/). |

### Vedi anche
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
