---
title: "FinanceFileType‑Klasse"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Definiert Finanzdokumenttypen."
type: docs
url: /de/python-net/groupdocs.conversion.filetypes/financefiletype/
is_root: false
weight: 90
---


## FinanceFileType class

Definiert Finanzdokumenttypen.

Enthält die folgenden Typen: [`FinanceFileType.xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/), [`FinanceFileType.i_xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/), [`FinanceFileType.ofx`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/). Erfahren Sie hier mehr über Finanzformate: https://docs.fileformat.com/finance/.

Der Typ FinanceFileType stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/__init__/) | Initialisiert ein FinanceFileType für die Serialisierung. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | Vergleicht das aktuelle Objekt mit einem anderen. (geerbt von [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | (geerbt von [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | Implementiert den Gleichheitsvergleich, der von [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/) definiert wird. (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | (geerbt von [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | (geerbt von [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | Ermittelt den FileType für die angegebene Dateierweiterung. (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | Gibt den FileType für den angegebenen file_name zurück. (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | Gibt den FileType für den bereitgestellten Dokumenten-Stream zurück. (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | (geerbt von [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | Stellt die Standard‑Hash‑Funktion bereit. (geerbt von [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | String-Darstellung des Dateityps. (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | Die Dateityp-Beschreibung. (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | Die Dateierweiterung. (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | Die Dateifamilie. (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | Das Dateiformat. (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Felder
| Feld | Beschreibung |
| :- | :- |
| [XBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/) | XBRL ist ein offener internationaler Standard für digitale Geschäftsberichte, der weltweit weit verbreitet ist. Es ist eine XML‑basierte Sprache, die XBRL‑Elemente, sogenannte Tags, verwendet, um jedes Element von Geschäftsdaten zu beschreiben und Daten für die Berichtssortierung und -analyse aufzubereiten. Erfahren Sie hier mehr über dieses Dateiformat. |
| [IXBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ixbrl/) | Im iXBRL werden die Inhalte von XBRL in das xHTML-Dateiformat eingebettet, das XML-Tags verwendet. Wie XBRL ist es das Wurzelelement von iXBRL-Dateien. Das XHTML-Format stellt seine Inhalte als Sammlung verschiedener Dokumenttypen und Module dar. Alle Dateien in XHTML basieren auf dem XML-Dateiformat und entsprechen den XML-Dokumentstandards. Erfahren Sie hier mehr über dieses Dateiformat. |
| [OFX](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/) | Open Financial Exchange (OFX) ist ein Datenstromformat zum Austausch finanzieller Informationen, das sich aus Microsofts Open Financial Connectivity (OFC) und Intuits Open Exchange-Dateiformaten entwickelt hat. Erfahren Sie hier mehr über dieses Dateiformat. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Unbekannter Dateityp (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Siehe auch
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
