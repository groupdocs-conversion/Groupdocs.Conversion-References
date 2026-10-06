---
title: "ProjectManagementFileType‑klass"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Definierar projektfilformat som skapas av projektledningsprogramvara såsom Microsoft Project, Primavera P6 etc."
type: docs
url: /sv/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/
is_root: false
weight: 170
---


## ProjectManagementFileType class

Definierar projektfilformat som skapas av projektledningsprogramvara såsom Microsoft Project, Primavera P6 etc.

En projektfil är en samling av uppgifter, resurser och deras schemaläggning för att få ett mätbart resultat i form av en produkt eller en tjänst. Projektledningsdokument. Inkluderar följande filtyper: [`ProjectManagementFileType.mpp`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp/), [`ProjectManagementFileType.mpt`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt/), [`ProjectManagementFileType.mpx`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx/). Läs mer om projektledningsformat här: https://wiki.fileformat.com/project-management.

ProjectManagementFileType‑typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/__init__/) | Initierar en ProjectManagementFileType för serialisering. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | Jämför aktuellt objekt med ett annat. (ärvd från [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | (ärvd från [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | Implementerar likhetsjämförelsen som definieras av [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/). (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | (ärvd från [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | (ärvd från [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | Hämtar FileType för den angivna filändelsen. (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | Returnerar FileType för angivet file_name. (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | Returnerar FileType för angivet dokumentström. (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | (ärvd från [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | Tillhandahåller standardhashfunktionen. (ärvd från [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | Strängrepresentation av filtyp. (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | Filtypens beskrivning. (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | Filändelsen. (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | Filfamiljen. (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | Filformatet. (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Fält
| Fält | Beskrivning |
| :- | :- |
| [MPT](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt/) | Microsoft Project‑mallfiler innehåller grundläggande information och struktur samt dokumentinställningar för att skapa .MPP‑filer. Läs mer om detta filformat här. |
| [MPP](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp/) | MPP är en Microsoft Project‑datafil som lagrar information relaterad till projektledning på ett integrerat sätt. Läs mer om detta filformat här. |
| [MPX](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx/) | Microsoft Exchange File Format är ett ASCII‑filformat för överföring av projektinformation mellan Microsoft Project (MSP) och andra applikationer som stödjer MPX‑filformatet, såsom Primavera Project Planner, Sciforma och Timerline Precision Estimating. Läs mer om detta filformat här. |
| [XER](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/xer/) | XER‑filformatet är ett proprietärt projektfilformat som används av Primavera P6‑programmet för projektplanering och -hantering. Läs mer om detta filformat här. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Okänd filtyp (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Se även
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
