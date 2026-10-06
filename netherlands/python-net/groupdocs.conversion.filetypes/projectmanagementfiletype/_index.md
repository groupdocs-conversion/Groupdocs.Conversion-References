---
title: "ProjectManagementFileType‑klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Definieert Project-bestandsformaten die worden aangemaakt door projectmanagementsoftware zoals Microsoft Project, Primavera P6 enz."
type: docs
url: /nl/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/
is_root: false
weight: 170
---


## ProjectManagementFileType class

Definieert Project-bestandsformaten die worden aangemaakt door projectmanagementsoftware zoals Microsoft Project, Primavera P6 enz.

Een projectbestand is een verzameling van taken, middelen en hun planning om een meetbaar resultaat te leveren in de vorm van een product of een dienst. Projectmanagementdocumenten. Bevat de volgende bestandstypen: [`ProjectManagementFileType.mpp`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp/), [`ProjectManagementFileType.mpt`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt/), [`ProjectManagementFileType.mpx`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx/). Meer informatie over projectmanagementformaten vindt u hier: https://wiki.fileformat.com/project-management.

Het type ProjectManagementFileType geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/__init__/) | Initialiseert een ProjectManagementFileType voor serialisatie. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | Vergelijkt het huidige object met een ander. (geërfd van [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | (geërfd van [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | Implementeert de gelijkheidsvergelijking gedefinieerd door [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/). (geërfd van [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (geërfd van [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | (geërfd van [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | (geërfd van [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | Haalt het FileType op voor de opgegeven bestandsextensie. (geërfd van [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | Retourneert FileType voor opgegeven file_name. (geërfd van [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | Retourneert FileType voor de opgegeven documentstroom. (geërfd van [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | (geërfd van [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (geërfd van [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | Biedt de standaard hash-functie. (geërfd van [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | Stringrepresentatie van bestandstype. (geërfd van [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | De beschrijving van het bestandstype. (geërfd van [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | De bestandsextensie. (geërfd van [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | De bestandsfamilie. (geërfd van [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | Het bestandsformaat. (geërfd van [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Velden
| Veld | Beschrijving |
| :- | :- |
| [MPT](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt/) | Microsoft Project‑sjabloonbestanden bevatten basisinformatie en structuur samen met documentinstellingen voor het maken van .MPP‑bestanden. Meer informatie over dit bestandsformaat vindt u hier. |
| [MPP](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp/) | MPP is een Microsoft Project‑databestand dat informatie met betrekking tot projectmanagement op een geïntegreerde manier opslaat. Meer informatie over dit bestandsformaat vindt u hier. |
| [MPX](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx/) | Microsoft Exchange‑bestandsformaat is een ASCII‑bestandsformaat voor het overdragen van projectinformatie tussen Microsoft Project (MSP) en andere toepassingen die het MPX‑bestandsformaat ondersteunen, zoals Primavera Project Planner, Sciforma en Timerline Precision Estimating. Meer informatie over dit bestandsformaat vindt u hier. |
| [XER](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/xer/) | Het XER‑bestandsformaat is een propriëtair projectbestandsformaat dat wordt gebruikt door de Primavera P6‑projectplanning‑ en -beheertoepassing. Meer informatie over dit bestandsformaat vindt u hier. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Onbekend bestandstype (geërfd van [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Zie ook
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
