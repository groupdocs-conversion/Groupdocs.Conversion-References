---
title: "Classe WordProcessingLoadOptions"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Fornisce opzioni per il caricamento dei documenti WordProcessing."
type: docs
url: /it/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/
is_root: false
weight: 580
---


## WordProcessingLoadOptions class

Fornisce opzioni per il caricamento dei documenti WordProcessing.

Pipeline di elaborazione dei caratteri:

Fase 1 - Sostituzione dei font (durante il caricamento del documento):
- Handles missing/unavailable fonts using FontSubstitutes, DefaultFont, and system substitution
- Processing order: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

Fase 2 - Sostituzione dei font (dopo il caricamento del documento):
- Modifies any existing fonts in the loaded document using FontReplacements
- Applied after all font substitution is complete

Il tipo WordProcessingLoadOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/__init__/) | Inizializza una nuova istanza di [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/). |

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
| [auto_detect_rtl_direction](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/) | La proprietà auto_detect_rtl_direction determina se i paragrafi e le run con testo prevalentemente da destra a sinistra hanno i loro flag bidi riparati prima della conversione. |
| [bookmark_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/bookmark_options/) | Le opzioni dei segnalibri. |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_built_in_document_properties/) | Il flag che indica se le proprietà del documento integrate vengono cancellate durante il caricamento di un documento Word processing. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_custom_document_properties/) | La proprietà ClearCustomDocumentProperties. |
| [comment_display_mode](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/comment_display_mode/) | La modalità di visualizzazione dei commenti specifica come i commenti devono essere mostrati nel documento di output. Il valore predefinito è `ShowInBalloons`. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owned/) | La proprietà implementa [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/). Il valore predefinito è False. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owner/) | Il flag convert_owner indica se convertire il proprietario del documento. Il valore predefinito è True. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/) | Il font predefinito per un documento WordProcessing. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/depth/) | La profondità delle opzioni di caricamento del contenitore del documento. Il valore predefinito è 1. |
| [embed_true_type_fonts](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/embed_true_type_fonts/) | La proprietà embed_true_type_fonts determina se i font TrueType sono incorporati nel documento di output. Il valore predefinito è True. |
| [font_config_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/) | La proprietà abilita la sostituzione automatica dei font mancanti basata sul FontConfig di sistema. Il valore predefinito è False. |
| [font_info_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/) | Il flag che abilita la sostituzione automatica dei font mancanti basata su FontInfo nel documento. Predefinito: False. |
| [font_name_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/) | La proprietà indica se i font mancanti vengono sostituiti automaticamente in base al nome del font. Predefinito: False. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/) | I sostituti dei font utilizzati durante la conversione di un documento WordProcessing. |
| [font_transformations](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_transformations/) | Le trasformazioni dei font applicate dopo il caricamento del documento e il completamento della sostituzione dei font, consentendo la modifica di tutti i font nel documento, inclusi quelli caricati correttamente. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/format/) | Il tipo di file del documento di input. |
| [hide_word_tracked_changes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hide_word_tracked_changes/) | La proprietà hide_word_tracked_changes nasconde il markup e le modifiche tracciate per i documenti Word. |
| [hyphenation_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenation_options/) | Le opzioni di sillabazione per i documenti WordProcessing. |
| [keep_date_field_original_value](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/keep_date_field_original_value/) | La proprietà keep_date_field_original_value determina se mantenere il valore originale di un campo data. Il valore predefinito è False. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/margin_settings/) | Le impostazioni dei margini. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/page_numbering/) | Il flag di generazione della numerazione di pagina per il documento convertito (predefinito: False). |
| [password](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/password/) | La password per rimuovere la protezione da un documento protetto. |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_document_structure/) | Il flag che indica se la struttura del documento deve essere preservata durante la conversione in PDF (il valore predefinito è False). |
| [preserve_form_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_form_fields/) | La proprietà indica se i campi modulo di Microsoft Word vengono preservati come campi modulo nel PDF risultante o convertiti in testo. Il valore predefinito è False. |
| [show_full_commenter_name](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/show_full_commenter_name/) | Il nome completo del commentatore viene mostrato nei commenti quando impostato su True. Il valore predefinito è False. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/size_settings/) | Le impostazioni di dimensione per il documento WordProcessing ([`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/)). |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/skip_external_resources/) | Il flag che determina se le risorse esterne vengono ignorate durante il caricamento di un documento. |
| [update_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_fields/) | L'opzione per aggiornare i campi dopo il caricamento. Predefinito: False. |
| [update_page_layout](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_page_layout/) | Il layout della pagina viene aggiornato dopo il caricamento. Predefinito: False. |
| [use_text_shaper](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/use_text_shaper/) | La proprietà indica se utilizzare un text shaper per una migliore visualizzazione del kerning. Il valore predefinito è False. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/whitelisted_resources/) | Le risorse nella whitelist per il caricamento di contenuti esterni, implementando [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |

### Esempio

```python
from groupdocs.conversion.options.load import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
load_options.password = "secret"
```

### Guides
Guide operative che utilizzano `WordProcessingLoadOptions`:

* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### Vedi anche
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
