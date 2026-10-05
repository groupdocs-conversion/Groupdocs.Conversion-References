---
title: "WordProcessingLoadOptions‑Klasse"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Bietet Optionen zum Laden von WordProcessing-Dokumenten."
type: docs
url: /de/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/
is_root: false
weight: 580
---


## WordProcessingLoadOptions class

Bietet Optionen zum Laden von WordProcessing-Dokumenten.

Schriftarten‑Verarbeitungspipeline:

Phase 1 – Schriftart-Substitution (während des Ladens des Dokuments):
- Handles missing/unavailable fonts using FontSubstitutes, DefaultFont, and system substitution
- Processing order: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

Phase 2 – Schriftart-Ersetzung (nach dem Laden des Dokuments):
- Modifies any existing fonts in the loaded document using FontReplacements
- Applied after all font substitution is complete

Der Typ WordProcessingLoadOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/__init__/) | Initialisiert eine neue Instanz von [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/). |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Bestimmt, ob zwei Objektinstanzen gleich sind. (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Dient als Standard‑Hash‑Funktion. (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [auto_detect_rtl_direction](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/) | Die auto_detect_rtl_direction-Eigenschaft bestimmt, ob Absätze und Läufe mit überwiegend rechts-nach-links‑Text ihre Bidi‑Flags vor der Konvertierung repariert werden. |
| [bookmark_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/bookmark_options/) | Die Lesezeichen-Optionen. |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_built_in_document_properties/) | Das Flag, das angibt, ob integrierte Dokumenteigenschaften beim Laden eines Word‑Verarbeitungsdokuments gelöscht werden. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/clear_custom_document_properties/) | Die ClearCustomDocumentProperties‑Eigenschaft. |
| [comment_display_mode](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/comment_display_mode/) | Der Kommentar-Anzeigemodus legt fest, wie Kommentare im Ausgabedokument angezeigt werden sollen. Standard ist `ShowInBalloons`. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owned/) | Die Eigenschaft implementiert [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/). Standard ist False. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/convert_owner/) | Das convert_owner-Flag gibt an, ob der Dokumentbesitzer konvertiert werden soll. Standard ist True. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/) | Die Standardschriftart für ein WordProcessing‑Dokument. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/depth/) | Die Tiefe der Dokument‑Container‑Ladeoptionen. Standard ist 1. |
| [embed_true_type_fonts](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/embed_true_type_fonts/) | Die embed_true_type_fonts‑Eigenschaft bestimmt, ob True‑Type‑Schriften im Ausgabedokument eingebettet werden. Standard ist True. |
| [font_config_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/) | Die Eigenschaft aktiviert die automatische Substitution fehlender Schriften basierend auf dem System‑FontConfig. Standard ist False. |
| [font_info_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/) | Das Flag, das die automatische Substitution fehlender Schriften basierend auf FontInfo im Dokument aktiviert. Standard: False. |
| [font_name_substitution_enabled](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_name_substitution_enabled/) | Die keep_date_field_original_value‑Eigenschaft gibt an, ob fehlende Schriften automatisch basierend auf dem Schriftnamen substituiert werden. Standard: False. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/) | Die Schriftart‑Ersetzungen, die beim Konvertieren eines WordProcessing‑Dokuments verwendet werden. |
| [font_transformations](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_transformations/) | Die Schriftart‑Transformationen, die nach Abschluss des Dokumentladens und der Schriftart‑Substitution angewendet werden und die Modifikation aller Schriften im Dokument ermöglichen, einschließlich der erfolgreich geladenen. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/format/) | Der Dateityp des Eingabedokuments. |
| [hide_word_tracked_changes](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hide_word_tracked_changes/) | Die hide_word_tracked_changes‑Eigenschaft blendet Markup und Nachverfolgungsänderungen für Word‑Dokumente aus. |
| [hyphenation_options](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenation_options/) | Die Silbentrennungs‑Optionen für WordProcessing‑Dokumente. |
| [keep_date_field_original_value](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/keep_date_field_original_value/) | Die keep_date_field_original_value‑Eigenschaft bestimmt, ob der ursprüngliche Wert eines Datumsfeldes beibehalten wird. Standard ist False. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/margin_settings/) | Die Rand‑Einstellungen. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/page_numbering/) | Das Seitenzahlen‑Generierungs‑Flag für das konvertierte Dokument (Standard: False). |
| [password](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/password/) | Das Passwort, um ein geschütztes Dokument zu entsperren. |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_document_structure/) | Das Flag, das angibt, ob die Dokumentstruktur beim Konvertieren in PDF erhalten bleiben soll (Standard ist False). |
| [preserve_form_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/preserve_form_fields/) | Die Eigenschaft gibt an, ob Microsoft‑Word‑Formularfelder im resultierenden PDF als Formularfelder erhalten bleiben oder in Text umgewandelt werden. Der Standardwert ist False. |
| [show_full_commenter_name](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/show_full_commenter_name/) | Der vollständige Kommentatorname wird in Kommentaren angezeigt, wenn er auf True gesetzt ist. Standard ist False. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/size_settings/) | Die Größeneinstellungen für das WordProcessing‑Dokument ([`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/)). |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/skip_external_resources/) | Das Flag, das festlegt, ob externe Ressourcen beim Laden eines Dokuments übersprungen werden. |
| [update_fields](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_fields/) | Die Option, Felder nach dem Laden zu aktualisieren. Standard: False. |
| [update_page_layout](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/update_page_layout/) | Das Seitenlayout wird nach dem Laden aktualisiert. Standard: False. |
| [use_text_shaper](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/use_text_shaper/) | Die Eigenschaft gibt an, ob ein Text‑Shaper für eine bessere Kerning‑Anzeige verwendet werden soll. Standard ist False. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/whitelisted_resources/) | Die whitelisted‑Ressourcen zum Laden externer Inhalte, implementiert durch [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |

### Beispiel

```python
from groupdocs.conversion.options.load import WordProcessingLoadOptions

load_options = WordProcessingLoadOptions()
load_options.password = "secret"
```

### Guides
Aufgaben‑Leitfäden, die `WordProcessingLoadOptions` verwenden:

* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### Siehe auch
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
