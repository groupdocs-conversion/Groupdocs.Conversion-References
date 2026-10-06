---
title: "classe EmailLoadOptions"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Fornisce opzioni per il caricamento di documenti Email."
type: docs
url: /it/python-net/groupdocs.conversion.options.load/emailloadoptions/
is_root: false
weight: 130
---


## EmailLoadOptions class

Fornisce opzioni per il caricamento di documenti Email.

Il tipo EmailLoadOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/__init__/) | Inizializza una nuova istanza della classe [`EmailLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/). |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/clone/) | Clona l'istanza corrente. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Determina se due istanze di oggetti sono uguali. (eredita da [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (eredita da [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (eredita da [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Funge da funzione hash predefinita. (eredita da [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [attachment_icons](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/attachment_icons/) | L'elenco delle icone di allegato, che può essere personalizzato per fornire icone specifiche per diversi tipi di file. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/convert_owned/) | La proprietà implementa [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/). Il valore predefinito è True. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/convert_owner/) | La proprietà convert_owner implementa [`IDocumentsContainerLoadOptions.convert_owner`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owner/). Il valore predefinito è True. |
| [custom_css_style](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/custom_css_style/) | Lo stile CSS personalizzato, che implementa [`ICustomCssStyleOptions.custom_css_style`](/conversion/python-net/groupdocs.conversion.options.load/icustomcssstyleoptions/custom_css_style/). |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/default_font/) | Il carattere predefinito per un documento email. Questo carattere verrà usato se un carattere richiesto è mancante. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/depth/) | La profondità delle opzioni di caricamento del contenitore di documenti. |
| [display_attachments](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_attachments/) | L'opzione per visualizzare o nascondere gli allegati nell'intestazione. Predefinito: True. |
| [display_bcc_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_bcc_email_address/) | L'opzione per visualizzare o nascondere l'indirizzo email Bcc. Predefinito: False. |
| [display_cc_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_cc_email_address/) | L'opzione per visualizzare o nascondere l'indirizzo email \"Cc\", impostata su False per impostazione predefinita. |
| [display_email_addresses](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_email_addresses/) | L'opzione per controllare se gli indirizzi email sono visualizzati accanto ai nomi. Il valore predefinito è True. |
| [display_from_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_from_email_address/) | L'opzione per visualizzare o nascondere l'indirizzo email \"from\". Predefinito: True. |
| [display_header](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_header/) | L'opzione per visualizzare o nascondere l'intestazione email. Predefinito: True. |
| [display_sent](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_sent/) | L'opzione per visualizzare o nascondere la data/ora di invio nell'intestazione. Il valore predefinito è True. |
| [display_subject](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_subject/) | L'opzione per visualizzare o nascondere l'oggetto nell'intestazione. Il valore predefinito è True. |
| [display_to_email_address](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/display_to_email_address/) | L'opzione per visualizzare o nascondere l'indirizzo email \"to\". Predefinito: True. |
| [field_text_map](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/field_text_map/) | La mappatura tra il messaggio email [`EmailField`](/conversion/python-net/groupdocs.conversion.options.load/emailfield/) e la rappresentazione testuale del campo. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/font_substitutes/) | L'elenco dei sostituti dei font. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/format/) | Il tipo di file del documento di input. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/margin_settings/) | Le impostazioni dei margini. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/orientation_settings/) | Le impostazioni di orientamento. |
| [page_layout_options](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/page_layout_options/) | La proprietà implementa [`IPageLayoutOptions.page_layout_options`](/conversion/python-net/groupdocs.conversion.options.load/ipagelayoutoptions/page_layout_options/). |
| [preserve_original_date](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/preserve_original_date/) | La proprietà determina se mantenere la stringa originale dell'intestazione della data nel messaggio di posta durante il salvataggio. Il valore predefinito è True. |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/resource_loading_timeout/) | Il timeout per il caricamento delle risorse esterne. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/size_settings/) | Le impostazioni della dimensione della pagina per l'operazione di caricamento email. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/skip_external_resources/) | La proprietà che implementa [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/). |
| [time_zone_offset](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/time_zone_offset/) | L'offset del Tempo Universale Coordinato (UTC) per le date dei messaggi. |
| [use_default_attachment_icons](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/use_default_attachment_icons/) | Il flag che indica se le icone predefinite degli allegati sono utilizzate (il valore predefinito è True). |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/emailloadoptions/whitelisted_resources/) | La proprietà implementa [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |

### Vedi anche
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
