---
title: "Classe WebLoadOptions"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Fornisce opzioni per il caricamento dei documenti web."
type: docs
url: /it/python-net/groupdocs.conversion.options.load/webloadoptions/
is_root: false
weight: 550
---


## WebLoadOptions class

Fornisce opzioni per il caricamento dei documenti web.

Il tipo WebLoadOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/__init__/) | Inizializza una nuova istanza di [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/). |

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
| [base_path](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/base_path/) | Il percorso/base URL per l'HTML. |
| [configure_headers](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/configure_headers/) | L'azione utilizzata per configurare le intestazioni della richiesta, dove il primo parametro è l'Uri. |
| [credentials_provider](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/credentials_provider/) | Il provider delle credenziali per l'Uri. |
| [custom_css_style](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/custom_css_style/) | La proprietà implementa [`ICustomCssStyleOptions.custom_css_style`](/conversion/python-net/groupdocs.conversion.options.load/icustomcssstyleoptions/custom_css_style/). |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/encoding/) | La codifica da utilizzare durante il caricamento del documento web. Se impostata su None, la codifica verrà determinata dall'attributo charset del documento. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/format/) | Il tipo di file del documento di input. |
| [html_rendering_mode](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/html_rendering_mode/) | La modalità di rendering HTML controlla come viene renderizzato il contenuto HTML. Predefinito: AbsolutePositioning. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/margin_settings/) | Le impostazioni dei margini. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/orientation_settings/) | Le impostazioni di orientamento. |
| [page_layout_options](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/page_layout_options/) | Le opzioni di layout di pagina utilizzate durante il caricamento dei documenti web. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/page_numbering/) | Il flag che abilita o disabilita la generazione della numerazione di pagina nel documento convertito. Predefinito: False. |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/resource_loading_timeout/) | Il timeout per il caricamento delle risorse esterne. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/size_settings/) | Le impostazioni di dimensione. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/skip_external_resources/) | La proprietà implementa [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/). |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/use_pdf/) | La proprietà indica se utilizzare PDF per la conversione (predefinito: False). |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/whitelisted_resources/) | La proprietà delle risorse in whitelist implementa [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |
| [zoom](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/zoom/) | Il livello di zoom come percentuale applicata al tag `<body>` del documento prima della conversione, scalando l'aspetto visivo del documento. |

### Vedi anche
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
