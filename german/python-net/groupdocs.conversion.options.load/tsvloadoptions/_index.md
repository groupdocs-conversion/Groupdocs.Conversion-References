---
title: "Klasse TsvLoadOptions"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Stellt Optionen zum Laden von TSV-Dokumenten dar."
type: docs
url: /de/python-net/groupdocs.conversion.options.load/tsvloadoptions/
is_root: false
weight: 480
---


## TsvLoadOptions class

Stellt Optionen zum Laden von TSV-Dokumenten dar.

Der Typ TsvLoadOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/__init__/) | Initialisiert eine neue Instanz von [`TsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/). |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | Klonen der aktuellen Instanz. (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Bestimmt, ob zwei Objektinstanzen gleich sind. (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Dient als Standard‑Hash‑Funktion. (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/clear_built_in_document_properties/) | Die Eigenschaft entfernt integrierte Metadaten‑Eigenschaften aus dem Dokument. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/clear_custom_document_properties/) | Die Eigenschaft, die benutzerdefinierte Metadaten‑Eigenschaften aus dem Dokument entfernt. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/convert_owned/) | Die Option, zu steuern, ob die im Dokumenten‑Container enthaltenen Dokumente konvertiert werden müssen. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/convert_owner/) | Die Option, zu steuern, ob der Container des Dokuments selbst konvertiert werden muss; wenn true, wird der Container das zuerst konvertierte Dokument sein. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/default_font/) | Die Schriftart, die verwendet wird, wenn eine Schriftart fehlt. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/depth/) | Die Option, zu steuern, wie viele Ebenen tief die Konvertierung durchgeführt werden soll. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/font_substitutes/) | Die Schriftart‑Ersetzungen. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/format/) | Der Dateityp des Eingabedokuments. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/margin_settings/) | Die Seitengrenz‑Einstellungen. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/size_settings/) | Die Seitengrößen‑Einstellungen. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/skip_external_resources/) | Die Eigenschaft bestimmt, ob externe Ressourcen geladen werden; wenn True, werden alle externen Ressourcen nicht geladen, außer denen in der [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/)‑Liste. Standard: True. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/whitelisted_resources/) | Die externen Ressourcen, die immer geladen werden. |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | Die Eigenschaft bestimmt, ob der gesamte Spalteninhalt eines Blatts im Ergebnis auf einer einzigen Seite dargestellt wird. (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | Die Zeilen werden beim Konvertieren automatisch angepasst. (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | Die Eigenschaft bestimmt, ob Excel‑Dateibeschränkungen beim Ändern von zellbezogenen Objekten geprüft werden. (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | Die Anzahl der Spalten pro Seite, die verwendet wird, um ein Arbeitsblatt in Seiten zu unterteilen; standardmäßig ist 0, was die Seitennummerierung deaktiviert. (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | Der Bereich, der beim Konvertieren in ein Nicht‑Tabellen‑Format umgewandelt wird, z. B. "D1:F8". (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | Die Systemkulturinformationen, die beim Laden der Datei verwendet werden. (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | Die Eigenschaft gibt an, ob Formelberechnungsfehler ignoriert werden sollen. Der Fehler kann eine nicht unterstützte Funktion, externe Links usw. sein. Standard ist False. (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | Die Eigenschaft gibt an, ob der Inhalt jedes Blatts in eine einzelne Seite im PDF-Dokument konvertiert wird. Standardwert ist True. (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | Die Konvertierung wird für kleinere Dateigröße statt für Druckqualität optimiert, wenn sie beim Konvertieren zu PDF auf True gesetzt ist. (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | Das Passwort, das zum Entschützen eines geschützten Dokuments verwendet wird. (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | Das Flag, das angibt, ob die Dokumentstruktur beim Konvertieren zu PDF erhalten bleiben soll (Standard ist False). (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | Die Art und Weise, wie Kommentare mit dem Blatt gedruckt werden. Standard ist PrintNoComments. (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | Die Schriftordner werden vor dem Laden des Dokuments zurückgesetzt. (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | Die Anzahl der Zeilen pro Seite, die verwendet wird, um ein Arbeitsblatt in Seiten zu teilen, wobei der Standardwert 0 keine Paginierung bedeutet. (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | Die Liste der Blattindizes, die konvertiert werden sollen. (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | Der Blattname, der konvertiert werden soll. (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | Die Option, Rasterlinien beim Konvertieren von Excel-Dateien anzuzeigen. (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | Die Option, ausgeblendete Blätter beim Konvertieren von Excel-Dateien anzuzeigen. (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | Die Einstellung, die beim Konvertieren leere Zeilen und Spalten überspringt. (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | Die Eigenschaft bestimmt, ob Fußzeilen beim Konvertieren von Tabellenkalkulationsdokumenten übersprungen werden. Standard: False. (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | Die Option, Kopfzeilen beim Konvertieren von Tabellenkalkulationsdokumenten zu überspringen. Standard: False. (geerbt von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)) |

### Siehe auch
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
