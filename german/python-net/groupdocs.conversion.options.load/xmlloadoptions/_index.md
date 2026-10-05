---
title: "XmlLoadOptions Klasse"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Die Optionen zum Laden von XML-Dokumenten."
type: docs
url: /de/python-net/groupdocs.conversion.options.load/xmlloadoptions/
is_root: false
weight: 590
---


## XmlLoadOptions class

Die Optionen zum Laden von XML-Dokumenten.

Der Typ XmlLoadOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/__init__/) | Initialisiert eine neue Instanz von [`XmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/). |

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
| [custom_css_style](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/custom_css_style/) | Der benutzerdefinierte CSS-Stil, der während der Konvertierung auf das Dokument angewendet wird. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/format/) | Der Dateityp des Eingabedokuments. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/margin_settings/) | Die Seitengrenz‑Einstellungen. |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/orientation_settings/) | Die Seitenausrichtungseinstellungen. |
| [page_layout_options](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/page_layout_options/) | Die Skalierung des Seitenlayouts, die beim Laden des Dokuments angewendet wird. Standard: None. |
| [page_numbering](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/page_numbering/) | Das Seitenzahlen‑Generierungs‑Flag für das konvertierte Dokument (Standard: False). |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/size_settings/) | Die Seitengrößen‑Einstellungen. |
| [skip_external_resources](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/skip_external_resources/) | Die Eigenschaft gibt an, ob externe Ressourcen geladen werden. |
| [use_as_data_source](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/use_as_data_source/) | Das XML-Dokument wird als Datenquelle verwendet. |
| [whitelisted_resources](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/whitelisted_resources/) | Die externen Ressourcen, die immer geladen werden. |
| [xsl_fo_factory](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/xsl_fo_factory/) | Der XSL-FO-Dokumenten-Stream zum Konvertieren von XML mithilfe einer XSL-FO-Markup-Datei. |
| [xslt_factory](/conversion/python-net/groupdocs.conversion.options.load/xmlloadoptions/xslt_factory/) | Der XSLT-Dokumenten-Stream zum Konvertieren von XML, wobei eine XSL-Transformation zu HTML durchgeführt wird. |
| [base_path](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/base_path/) | Der Basis-Pfad/URL für das HTML. (geerbt von [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [configure_headers](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/configure_headers/) | Die Aktion, die zum Konfigurieren von Anforderungs-Headern verwendet wird, wobei der erste Parameter die Uri ist. (geerbt von [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [credentials_provider](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/credentials_provider/) | Der Anmeldeinformationen‑Provider für die Uri. (geerbt von [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/encoding/) | Die zu verwendende Kodierung beim Laden des Webdokuments. Wenn sie auf None gesetzt ist, wird die Kodierung aus dem Zeichen­satz‑Attribut des Dokuments ermittelt. (geerbt von [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [html_rendering_mode](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/html_rendering_mode/) | Der HTML‑Rendermodus steuert, wie HTML‑Inhalt gerendert wird. Standard: AbsolutePositioning. (geerbt von [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [resource_loading_timeout](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/resource_loading_timeout/) | Das Zeitlimit für das Laden externer Ressourcen. (geerbt von [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/use_pdf/) | Die Eigenschaft gibt an, ob PDF für die Konvertierung verwendet werden soll (Standard: False). (geerbt von [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |
| [zoom](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/zoom/) | Der Zoom‑Wert als Prozentsatz, der vor der Konvertierung auf das `<body>`‑Tag des Dokuments angewendet wird und das visuelle Erscheinungsbild des Dokuments skaliert. (geerbt von [`WebLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/webloadoptions/)) |

### Siehe auch
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
