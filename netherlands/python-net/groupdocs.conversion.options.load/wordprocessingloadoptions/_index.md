---
title: "WordProcessingLoadOptions klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Biedt opties voor het laden van WordProcessing-documenten."
type: docs
url: /nl/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/
is_root: false
weight: 580
---


## WordProcessingLoadOptions class

Biedt opties voor het laden van WordProcessing-documenten.

Lettertypeverwerkingspipeline:

Fase 1 - Lettertypevervanging (tijdens het laden van het document):
- Handles missing/unavailable fonts using FontSubstitutes, DefaultFont, and system substitution
- Processing order: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

Fase 2 - Lettertypevervanging (na het laden van het document):
- Modifies any existing fonts in the loaded document using FontReplacements
- Applied after all font substitution is complete

Het type WordProcessingLoadOptions bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/__init__/) | Initialiseert een nieuw exemplaar van [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/). |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Bepaalt of twee objectinstellingen gelijk zijn. (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Dient als de standaard hash-functie. (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [auto_detect_rtl_direction](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/) | De auto_detect_rtl_direction eigenschap bepaalt of alinea's en runs met overwegend rechts-naar-links tekst hun bidi‑vlaggen vóór conversie worden gerepareerd. |
| [bookmark_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/bookmark_options/) | De bladwijzeropties. |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_built_in_document_properties/) | De vlag die aangeeft of ingebouwde documenteigenschappen worden gewist bij het laden van een Word‑verwerkingsdocument. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_custom_document_properties/) | De eigenschap ClearCustomDocumentProperties. |
| [comment_display_mode](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/comment_display_mode/) | De weergavemodus voor opmerkingen geeft aan hoe opmerkingen moeten worden weergegeven in het uitvoerdocument. Standaard is `ShowInBalloons`. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owned/) | De eigenschap implementeert [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/). Standaard is False. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owner/) | De vlag convert_owner geeft aan of de documenteigenaar moet worden geconverteerd. Standaard is True. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/) | Het standaardlettertype voor een WordProcessing‑document. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/depth/) | De diepte van de laadopties voor de documentcontainer. Standaard is 1. |
| [embed_true_type_fonts](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/embed_true_type_fonts/) | De embed_true_type_fonts eigenschap bepaalt of TrueType‑lettertypen worden ingebed in het uitvoerdocument. Standaard is True. |
| [font_config_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/) | De eigenschap schakelt automatische vervanging van ontbrekende lettertypen in op basis van de systeem‑FontConfig. Standaard is False. |
| [font_info_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/) | De vlag die automatische vervanging van ontbrekende lettertypen op basis van FontInfo in het document inschakelt. Standaard: False. |
| [font_name_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/) | De eigenschap geeft aan of ontbrekende lettertypen automatisch worden vervangen op basis van de lettertype‑naam. Standaard: False. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/) | De lettertype‑substituten die worden gebruikt bij het converteren van een WordProcessing‑document. |
| [font_transformations](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_transformations/) | De lettertype‑transformaties die worden toegepast nadat het laden van het document en de lettertypevervanging voltooid zijn, waardoor elke lettertype in het document kan worden aangepast, inclusief die succesvol geladen zijn. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/format/) | Het type invoerdocumentbestand. |
| [hide_word_tracked_changes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hide_word_tracked_changes/) | De hide_word_tracked_changes eigenschap verbergt markup en revisies voor Word‑documenten. |
| [hyphenation_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenation_options/) | De afbreekopties voor WordProcessing‑documenten. |
| [keep_date_field_original_value](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/keep_date_field_original_value/) | De keep_date_field_original_value eigenschap bepaalt of de oorspronkelijke waarde van een datumveld behouden blijft. Standaard is False. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/margin_settings/) | De margesettings. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/page_numbering/) | De vlag voor paginanummergeneratie voor het geconverteerde document (standaard: False). |
| [password](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/password/) | Het wachtwoord om een beveiligd document te ontgrendelen. |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_document_structure/) | De vlag die aangeeft of de documentstructuur behouden moet blijven bij het converteren naar PDF (standaard is False). |
| [preserve_form_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_form_fields/) | De eigenschap geeft aan of Microsoft Word-formuliervelden behouden blijven als formuliervelden in de resulterende PDF of worden geconverteerd naar tekst. Standaard is False. |
| [show_full_commenter_name](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/show_full_commenter_name/) | De volledige naam van de commentator wordt weergegeven in opmerkingen wanneer deze op True is ingesteld. Standaard is False. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/size_settings/) | De grootte-instellingen voor het WordProcessing-document ([`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/)). |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/skip_external_resources/) | De vlag die bepaalt of externe bronnen worden overgeslagen bij het laden van een document. |
| [update_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_fields/) | De optie om velden bij te werken na het laden. Standaard: False. |
| [update_page_layout](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_page_layout/) | De paginalay-out wordt bijgewerkt na het laden. Standaard: False. |
| [use_text_shaper](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/use_text_shaper/) | De eigenschap geeft aan of een tekstvormer moet worden gebruikt voor een betere weergave van kerning. Standaard is False. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/whitelisted_resources/) | De witte lijst met bronnen voor het laden van externe inhoud, implementerend [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |

### Voorbeeld

```python
from groupdocs.conversion.options.load import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
load_options.password = "secret"
```

### Guides
Taakgidsen die `WordProcessingLoadOptions` gebruiken:

* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### Zie ook
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
