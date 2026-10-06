---
title: "WordProcessingLoadOptions-klass"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Tillhandahåller alternativ för att ladda WordProcessing-dokument."
type: docs
url: /sv/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/
is_root: false
weight: 580
---


## WordProcessingLoadOptions class

Tillhandahåller alternativ för att ladda WordProcessing-dokument.

Typsnittshanteringspipeline:

Fas 1 - Teckensnittssubstitution (under dokumentladdning):
- Handles missing/unavailable fonts using FontSubstitutes, DefaultFont, and system substitution
- Processing order: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

Fas 2 - Teckensnittsersättning (efter dokumentladdning):
- Modifies any existing fonts in the loaded document using FontReplacements
- Applied after all font substitution is complete

Typen WordProcessingLoadOptions exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/__init__/) | Initierar en ny instans av [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/). |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Bestämmer om två objektinstanser är lika. (ärvd från [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (ärvd från [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (ärvd från [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Fungerar som standard‑hashfunktion. (ärvd från [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [auto_detect_rtl_direction](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/) | Egenskapen auto_detect_rtl_direction bestämmer om stycken och körningar med huvudsakligen höger‑till‑vänster‑text har sina bidi‑flaggor reparerade före konvertering. |
| [bookmark_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/bookmark_options/) | Bokmärkesalternativen. |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_built_in_document_properties/) | Flaggan som indikerar om inbyggda dokumentegenskaper rensas när ett Word‑behandlingsdokument laddas. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_custom_document_properties/) | Egenskapen ClearCustomDocumentProperties. |
| [comment_display_mode](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/comment_display_mode/) | Kommentarsvisningsläget specificerar hur kommentarer ska visas i utdokumentet. Standard är `ShowInBalloons`. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owned/) | Egenskapen implementerar [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/). Standard är False. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owner/) | Flaggan convert_owner indikerar om dokumentägaren ska konverteras. Standard är True. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/) | Standardteckensnittet för ett WordProcessing‑dokument. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/depth/) | Djupet för dokumentbehållarens laddningsalternativ. Standard är 1. |
| [embed_true_type_fonts](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/embed_true_type_fonts/) | Egenskapen embed_true_type_fonts bestämmer om TrueType‑teckensnitt bäddas in i utdokumentet. Standard är True. |
| [font_config_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/) | Egenskapen möjliggör automatisk ersättning av saknade teckensnitt baserat på systemets FontConfig. Standard är False. |
| [font_info_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/) | Flaggan som möjliggör automatisk ersättning av saknade teckensnitt baserat på FontInfo i dokumentet. Standard: False. |
| [font_name_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/) | Egenskapen indikerar om saknade teckensnitt automatiskt ersätts baserat på teckensnittsnamnet. Standard: False. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/) | Teckensnittsersättningar som används vid konvertering av ett WordProcessing‑dokument. |
| [font_transformations](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_transformations/) | Teckensnittstransformationerna som tillämpas efter att dokumentladdning och teckensnittssubstitution är slutförda, vilket möjliggör modifiering av alla teckensnitt i dokumentet, inklusive de som laddades framgångsrikt. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/format/) | Inmatningsdokumentets filtyp. |
| [hide_word_tracked_changes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hide_word_tracked_changes/) | Egenskapen hide_word_tracked_changes döljer markup och spårade ändringar för Word‑dokument. |
| [hyphenation_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenation_options/) | Avstavningsalternativen för WordProcessing‑dokument. |
| [keep_date_field_original_value](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/keep_date_field_original_value/) | Egenskapen keep_date_field_original_value bestämmer om det ursprungliga värdet för ett datumfält behålls. Standard är False. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/margin_settings/) | Marginalinställningarna. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/page_numbering/) | Flaggan för sidnumreringsgenerering för det konverterade dokumentet (standard: False). |
| [password](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/password/) | Lösenordet för att avskydda ett skyddat dokument. |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_document_structure/) | Flaggan som indikerar om dokumentstrukturen ska bevaras vid konvertering till PDF (standard är False). |
| [preserve_form_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_form_fields/) | Egenskapen indikerar om Microsoft Word-formulärfält bevaras som formulärfält i den resulterande PDF-filen eller konverteras till text. Standard är False. |
| [show_full_commenter_name](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/show_full_commenter_name/) | Det fullständiga kommentatornamnet visas i kommentarer när det är satt till True. Standard är False. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/size_settings/) | Storleksinställningarna för WordProcessing-dokumentet ([`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/)). |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/skip_external_resources/) | Flaggan som bestämmer om externa resurser hoppas över när ett dokument laddas. |
| [update_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_fields/) | Alternativet att uppdatera fält efter laddning. Standard: False. |
| [update_page_layout](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_page_layout/) | Sidlayouten uppdateras efter laddning. Standard: False. |
| [use_text_shaper](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/use_text_shaper/) | Egenskapen indikerar om en textformare ska användas för bättre kerningvisning. Standard är False. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/whitelisted_resources/) | De vitlistade resurserna för att ladda externt innehåll, implementerar [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |

### Exempel

```python
from groupdocs.conversion.options.load import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
load_options.password = "secret"
```

### Guides
Uppgiftsguider som använder `WordProcessingLoadOptions`:

* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### Se även
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
