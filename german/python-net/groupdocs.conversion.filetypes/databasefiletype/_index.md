---
title: "DatabaseFileType Klasse"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Definiert Datenbankdokumente."
type: docs
url: /de/python-net/groupdocs.conversion.filetypes/databasefiletype/
is_root: false
weight: 40
---


## DatabaseFileType class

Definiert Datenbankdokumente. Enthält die folgenden Dateitypen.

- [`DatabaseFileType.nsf`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/nsf/)
- [`DatabaseFileType.log`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/log/)
- [`DatabaseFileType.sql`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/sql/)

Der Typ DatabaseFileType stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/__init__/) | Initialisiert einen neuen DatabaseFileType für die Serialisierung. |

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
| [NSF](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/nsf/) | Eine Datei mit der Erweiterung .nsf (Notes Storage Facility) ist ein Datenbankdateiformat, das von der IBM Notes‑Software verwendet wird, die zuvor als Lotus Notes bekannt war. Sie definiert das Schema zum Speichern verschiedener Arten von Objekten wie E‑Mails, Terminen, Dokumenten, Formularen und Ansichten. Erfahren Sie hier mehr über dieses Dateiformat. |
| [LOG](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/log/) | Eine Datei mit der Erweiterung .log enthält eine Liste von Klartext mit Zeitstempel. In der Regel werden bestimmte Aktivitätsdetails von Software oder Betriebssystemen protokolliert, um Entwicklern oder Benutzern zu helfen, nachzuvollziehen, was in einem bestimmten Zeitraum passiert ist. Erfahren Sie hier mehr über dieses Dateiformat. |
| [SQL](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/sql/) | Eine Datei mit der Erweiterung .sql ist eine Structured Query Language (SQL)‑Datei, die Code enthält, um mit relationalen Datenbanken zu arbeiten. Sie wird verwendet, um SQL‑Anweisungen für CRUD‑Operationen (Create, Read, Update und Delete) auf Datenbanken zu schreiben. Erfahren Sie hier mehr über dieses Dateiformat. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Unbekannter Dateityp (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Siehe auch
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
