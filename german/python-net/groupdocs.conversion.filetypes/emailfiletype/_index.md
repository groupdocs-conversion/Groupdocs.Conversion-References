---
title: "EmailFileType‑Klasse"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Definiert E‑Mail‑Dateiformate, die von E‑Mail‑Anwendungen zum Speichern von Nachrichten, Anhängen, Ordnern, Adressbüchern und anderen Daten verwendet werden."
type: docs
url: /de/python-net/groupdocs.conversion.filetypes/emailfiletype/
is_root: false
weight: 70
---


## EmailFileType class

Definiert E‑Mail‑Dateiformate, die von E‑Mail‑Anwendungen zum Speichern von Nachrichten, Anhängen, Ordnern, Adressbüchern und anderen Daten verwendet werden.

Enthält die folgenden Dateitypen:
- [`EmailFileType.eml`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml/)
- [`EmailFileType.emlx`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx/)
- [`EmailFileType.msg`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg/)
- [`EmailFileType.vcf`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf/)
- [`EmailFileType.mbox`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox/)
- [`EmailFileType.pst`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst/)
- [`EmailFileType.ost`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost/)
- [`EmailFileType.olm`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm/)

Erfahren Sie mehr über E‑Mail‑Formate unter https://wiki.fileformat.com/email.

Der Typ EmailFileType stellt die folgenden Member bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/__init__/) | Initialisiert ein neues EmailFileType für die Serialisierung. |

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
| [MSG](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg/) | MSG ist ein Dateiformat, das von Microsoft Outlook und Exchange verwendet wird, um E‑Mail‑Nachrichten, Kontakte, Termine oder andere Aufgaben zu speichern. Erfahren Sie hier mehr über dieses Dateiformat. |
| [EML](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml/) | Das EML‑Dateiformat stellt E‑Mail‑Nachrichten dar, die mit Outlook und anderen relevanten Anwendungen gespeichert wurden. Fast alle E‑Mail‑Clients unterstützen dieses Dateiformat, da es dem RFC‑822‑Internet‑Message‑Format‑Standard entspricht. Erfahren Sie hier mehr über dieses Dateiformat. |
| [EMLX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx/) | Das EMLX‑Dateiformat wird von Apple implementiert und entwickelt. Die Apple‑Mail‑Anwendung verwendet das EMLX‑Dateiformat zum Exportieren von E‑Mails. Erfahren Sie hier mehr über dieses Dateiformat. |
| [VCF](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf/) | VCF (Virtual Card Format) oder vCard ist ein digitales Dateiformat zum Speichern von Kontaktinformationen. Das Format wird häufig für den Datenaustausch zwischen beliebten Informationsaustausch‑Anwendungen verwendet. Erfahren Sie hier mehr über dieses Dateiformat. |
| [MBOX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox/) | MBox‑Dateiformat ist ein allgemeiner Begriff, der einen Container für eine Sammlung von elektronischen Mail‑Nachrichten bezeichnet. Die Nachrichten werden zusammen mit ihren Anhängen im Container gespeichert. Erfahren Sie hier mehr über dieses Dateiformat. |
| [PST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst/) | Dateien mit der Erweiterung .PST stellen Outlook Personal Storage Files (auch Personal Storage Table genannt) dar, die verschiedene Benutzerdaten speichern. Erfahren Sie hier mehr über dieses Dateiformat. |
| [OST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost/) | OST‑ oder Offline‑Storage‑Dateien stellen die Postfachdaten eines Benutzers im Offline‑Modus auf dem lokalen Rechner dar, nachdem er sich mit dem Exchange‑Server über Microsoft Outlook registriert hat. Erfahren Sie hier mehr über dieses Dateiformat. |
| [OLM](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm/) | Eine Datei mit der Erweiterung .olm ist eine Microsoft‑Outlook‑Datei für das Mac‑Betriebssystem. Eine OLM‑Datei speichert E‑Mail‑Nachrichten, Journale, Kalenderdaten und andere Anwendungsdaten. Sie ist ähnlich zu PST‑Dateien, die von Outlook unter Windows verwendet werden. OLM‑Dateien, die von Outlook für Mac erstellt wurden, können jedoch nicht in Outlook für Windows geöffnet werden. Erfahren Sie hier mehr über dieses Dateiformat. |
| [ICS](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ics/) | Das ICS‑ (iCalendar‑)Dateiformat wird verwendet, um Kalender‑ und Terminplanungsinformationen wie Ereignisse, Aufgaben und Frei‑/Belegt‑Daten darzustellen und auszutauschen. Erfahren Sie hier mehr über dieses Dateiformat. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Unbekannter Dateityp (geerbt von [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Siehe auch
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
