---
title: "ProjectManagementFileType‑Klasse"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Definiert Projektdateiformate, die von Projektmanagement-Software wie Microsoft Project, Primavera P6 usw. erstellt werden."
type: docs
url: /de/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/
is_root: false
weight: 170
---


## ProjectManagementFileType class

Definiert Projektdateiformate, die von Projektmanagement-Software wie Microsoft Project, Primavera P6 usw. erstellt werden.

Eine Projektdatei ist eine Sammlung von Aufgaben, Ressourcen und deren Zeitplanung, um ein messbares Ergebnis in Form eines Produkts oder einer Dienstleistung zu erzielen. Projektmanagement‑Dokumente. Enthält die folgenden Dateitypen: [`ProjectManagementFileType.mpp`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp/), [`ProjectManagementFileType.mpt`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt/), [`ProjectManagementFileType.mpx`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx/). Erfahren Sie hier mehr über Projektmanagement‑Formate: https://wiki.fileformat.com/project-management.

Der Typ ProjectManagementFileType stellt die folgenden Member bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/__init__/) | Initialisiert ein ProjectManagementFileType für die Serialisierung. |

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
| [MPT](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt/) | Microsoft‑Project‑Vorlagendateien enthalten grundlegende Informationen und Strukturen sowie Dokumenteinstellungen zum Erstellen von .MPP‑Dateien. Erfahren Sie hier mehr über dieses Dateiformat. |
| [MPP](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp/) | MPP ist eine Microsoft Project‑Datendatei, die Informationen im Zusammenhang mit Projektmanagement in integrierter Weise speichert. Erfahren Sie hier mehr über dieses Dateiformat. |
| [MPX](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx/) | Microsoft Exchange File Format ist ein ASCII‑Dateiformat zum Übertragen von Projektinformationen zwischen Microsoft Project (MSP) und anderen Anwendungen, die das MPX‑Dateiformat unterstützen, wie Primavera Project Planner, Sciforma und Timerline Precision Estimating. Erfahren Sie hier mehr über dieses Dateiformat. |
| [XER](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/xer/) | Das XER‑Dateiformat ist ein proprietäres Projektdateiformat, das von der Primavera P6 Projektplanungs‑ und Managementanwendung verwendet wird. Erfahren Sie hier mehr über dieses Dateiformat. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Unbekannter Dateityp (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Siehe auch
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
