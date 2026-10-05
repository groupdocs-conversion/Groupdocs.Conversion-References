---
title: "Klasse SpreadsheetLoadOptions"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Bietet Optionen zum Laden von Tabellenkalkulationsdokumenten."
type: docs
url: /de/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/
is_root: false
weight: 440
---


## SpreadsheetLoadOptions class

Bietet Optionen zum Laden von Tabellenkalkulationsdokumenten.

Der Typ SpreadsheetLoadOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/__init__/) | Initialisiert eine neue Instanz von [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/). |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clone/) | Klonen der aktuellen Instanz. |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Bestimmt, ob zwei Objektinstanzen gleich sind. (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Dient als Standard‑Hash‑Funktion. (geerbt von [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/all_columns_in_one_page_per_sheet/) | Die Eigenschaft bestimmt, ob der gesamte Spalteninhalt eines Blatts im Ergebnis auf einer einzigen Seite dargestellt wird. |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/auto_fit_rows/) | Die Zeilen werden beim Konvertieren automatisch angepasst. |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/) | Die Eigenschaft bestimmt, ob Excel‑Dateibeschränkungen beim Ändern von zellbezogenen Objekten geprüft werden. |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clear_built_in_document_properties/) | Die Eigenschaft ClearBuiltInDocumentProperties bestimmt, ob integrierte Dokumenteigenschaften beim Laden einer Tabellenkalkulation gelöscht werden. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/clear_custom_document_properties/) | Die ClearCustomDocumentProperties‑Eigenschaft. |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/columns_per_page/) | Die Anzahl der Spalten pro Seite, die zum Aufteilen eines Arbeitsblatts in Seiten verwendet wird; Standard ist 0, was die Seitennummerierung deaktiviert. |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_owned/) | Die Eigenschaft implementiert [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owned/) und ist standardmäßig False. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_owner/) | Die Eigenschaft, die [`IDocumentsContainerLoadOptions.convert_owner`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions/convert_owner/) implementiert. Standard ist True. |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/convert_range/) | Der Bereich, der beim Konvertieren in ein Nicht‑Tabellenkalkulationsformat zu konvertieren ist, z. B. "D1:F8". |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/culture_info/) | Die Systemkulturinformationen, die beim Laden der Datei verwendet werden. |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/default_font/) | Die Standardschriftart für ein Tabellendokument. |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/depth/) | Die Tiefe der Ladeoptionen des Dokumentencontainers. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/font_substitutes/) | Die Schriftartersatzwerte, die beim Konvertieren eines Tabellendokuments verwendet werden. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/format/) | Der Dateityp des Eingabedokuments. |
| [ignore_formula_calculation_errors](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/ignore_formula_calculation_errors/) | Die Eigenschaft gibt an, ob Formelberechnungsfehler ignoriert werden sollen. Der Fehler kann eine nicht unterstützte Funktion, externe Links usw. sein. Standard ist False. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/margin_settings/) | Die Rand‑Einstellungen. |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/one_page_per_sheet/) | Die Eigenschaft gibt an, ob der Inhalt jedes Blatts in eine einzelne Seite im PDF-Dokument konvertiert wird. Der Standardwert ist True. |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/optimize_pdf_size/) | Die Konvertierung ist auf kleinere Dateigröße statt Druckqualität optimiert, wenn sie beim Konvertieren zu PDF auf True gesetzt wird. |
| [password](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/password/) | Das Passwort, das verwendet wird, um ein geschütztes Dokument zu entsperren. |
| [preserve_document_structure](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/preserve_document_structure/) | Das Flag, das angibt, ob die Dokumentstruktur beim Konvertieren in PDF erhalten bleiben soll (Standard ist False). |
| [print_comments](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/print_comments/) | Die Art und Weise, wie Kommentare mit dem Blatt gedruckt werden. Standard ist PrintNoComments. |
| [reset_font_folders](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/reset_font_folders/) | Die Schriftordner werden vor dem Laden des Dokuments zurückgesetzt. |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/rows_per_page/) | Die Anzahl der Zeilen pro Seite, die verwendet wird, um ein Arbeitsblatt in Seiten zu unterteilen, wobei der Standardwert 0 bedeutet, dass keine Seitenteilung erfolgt. |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheet_indexes/) | Die Liste der Blattindizes, die konvertiert werden sollen. |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/sheets/) | Der Blattname, der konvertiert werden soll. |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_grid_lines/) | Die Option, Gitternetzlinien beim Konvertieren von Excel-Dateien anzuzeigen. |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/show_hidden_sheets/) | Die Option, ausgeblendete Blätter beim Konvertieren von Excel-Dateien anzuzeigen. |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/size_settings/) | Die Größeneinstellungen, wie definiert von [`IPageSizeOptions`](/conversion/python-net/groupdocs.conversion.options/ipagesizeoptions/). |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_empty_rows_and_columns/) | Die Einstellung, die beim Konvertieren leere Zeilen und Spalten überspringt. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_external_resources/) | Die Eigenschaft implementiert [`IResourceLoadingOptions.skip_external_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/skip_external_resources/). |
| [skip_footers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_footers/) | Die Eigenschaft bestimmt, ob Fußzeilen beim Konvertieren von Tabellendokumenten übersprungen werden. Standard: False. |
| [skip_headers](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/skip_headers/) | Die Option, Kopfzeilen beim Konvertieren von Tabellendokumenten zu überspringen. Standard: False. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/whitelisted_resources/) | Die freigegebenen Ressourcen, wie definiert von [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/). |

### Siehe auch
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
