---
title: "EmailFileType‑klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Definieert e-mailbestandsformaten die door e-mailtoepassingen worden gebruikt om berichten, bijlagen, mappen, adresboeken en andere gegevens op te slaan."
type: docs
url: /nl/python-net/groupdocs.conversion.filetypes/emailfiletype/
is_root: false
weight: 70
---


## EmailFileType class

Definieert e-mailbestandsformaten die door e-mailtoepassingen worden gebruikt om berichten, bijlagen, mappen, adresboeken en andere gegevens op te slaan.

Bevat de volgende bestandstypen:
- [`EmailFileType.eml`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml/)
- [`EmailFileType.emlx`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx/)
- [`EmailFileType.msg`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg/)
- [`EmailFileType.vcf`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf/)
- [`EmailFileType.mbox`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox/)
- [`EmailFileType.pst`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst/)
- [`EmailFileType.ost`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost/)
- [`EmailFileType.olm`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm/)

Leer meer over e‑mailformaten op https://wiki.fileformat.com/email.

Het EmailFileType‑type maakt de volgende leden beschikbaar:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/__init__/) | Initialiseert een nieuwe EmailFileType voor serialisatie. |

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
| [MSG](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg/) | MSG is een bestandsformaat dat door Microsoft Outlook en Exchange wordt gebruikt om e‑mailberichten, contactpersonen, afspraken of andere taken op te slaan. Leer meer over dit bestandsformaat hier. |
| [EML](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml/) | EML‑bestandsformaat vertegenwoordigt e‑mailberichten die zijn opgeslagen met Outlook en andere relevante applicaties. Bijna alle e‑mailclients ondersteunen dit bestandsformaat vanwege de naleving van de RFC‑822 Internet Message Format‑standaard. Leer meer over dit bestandsformaat hier. |
| [EMLX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx/) | Het EMLX‑bestandsformaat is geïmplementeerd en ontwikkeld door Apple. De Apple Mail‑applicatie gebruikt het EMLX‑bestandsformaat voor het exporteren van e‑mails. Leer meer over dit bestandsformaat hier. |
| [VCF](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf/) | VCF (Virtual Card Format) of vCard is een digitaal bestandsformaat voor het opslaan van contactinformatie. Het formaat wordt veel gebruikt voor gegevensuitwisseling tussen populaire informatie‑uitwisselingsapplicaties. Leer meer over dit bestandsformaat hier. |
| [MBOX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox/) | MBox‑bestandsformaat is een algemene term die een container voor een verzameling elektronische e‑mailberichten vertegenwoordigt. De berichten worden in de container opgeslagen samen met hun bijlagen. Leer meer over dit bestandsformaat hier. |
| [PST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst/) | Bestanden met de .PST‑extensie vertegenwoordigen Outlook Personal Storage Files (ook wel Personal Storage Table genoemd) die diverse gebruikersinformatie opslaan. Leer meer over dit bestandsformaat hier. |
| [OST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost/) | OST‑ of Offline Storage‑bestanden vertegenwoordigen de mailboxgegevens van een gebruiker in offline‑modus op de lokale machine na registratie bij Exchange Server met Microsoft Outlook. Leer meer over dit bestandsformaat hier. |
| [OLM](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm/) | Een bestand met de .olm‑extensie is een Microsoft Outlook‑bestand voor het macOS. Een OLM‑bestand slaat e‑mailberichten, journaals, agenda‑gegevens en andere soorten toepassingsgegevens op. Deze lijken op PST‑bestanden die door Outlook op Windows‑besturingssystemen worden gebruikt. OLM‑bestanden die door Outlook voor Mac zijn aangemaakt, kunnen echter niet worden geopend in Outlook voor Windows. Leer meer over dit bestandsformaat hier. |
| [ICS](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ics/) | ICS (iCalendar)‑bestandsformaat wordt gebruikt om agenda‑ en planningsinformatie zoals evenementen, taken en vrije/bezette gegevens te vertegenwoordigen en uit te wisselen. Leer meer over dit bestandsformaat hier. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Onbekend bestandstype (geërfd van [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Zie ook
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
