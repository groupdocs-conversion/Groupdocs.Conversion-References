---
title: "FinanceFileType‑klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Definieert financiëledocumenttypen."
type: docs
url: /nl/python-net/groupdocs.conversion.filetypes/financefiletype/
is_root: false
weight: 90
---


## FinanceFileType class

Definieert financiëledocumenttypen.

Bevat de volgende typen: [`FinanceFileType.xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/), [`FinanceFileType.i_xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/), [`FinanceFileType.ofx`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/). Meer informatie over financiële formaten vind je hier: https://docs.fileformat.com/finance/.

Het type FinanceFileType bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/__init__/) | Initialiseert een FinanceFileType voor serialisatie. |

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
| [XBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/) | XBRL is een open internationale standaard voor digitale bedrijfsrapportage die wereldwijd veel wordt gebruikt. Het is een op XML gebaseerde taal die XBRL‑elementen, bekend als tags, gebruikt om elk item van bedrijfsgegevens te beschrijven en gegevens te formuleren voor het sorteren en analyseren van rapporten. Meer informatie over dit bestandsformaat vind je hier. |
| [IXBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ixbrl/) | Binnen iXBRL worden de inhoud van XBRL verpakt in het xHTML‑bestandsformaat dat XML‑tags gebruikt. Net als XBRL is het het basiselement van iXBRL‑bestanden. Het XHTML‑formaat vertegenwoordigt de inhoud als een verzameling van verschillende documenttypen en modules. Alle bestanden in XHTML zijn gebaseerd op het XML‑bestandsformaat en voldoen aan de XML‑documentstandaarden. Meer informatie over dit bestandsformaat vind je hier. |
| [OFX](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/) | Open Financial Exchange (OFX) is een datastroomformaat voor het uitwisselen van financiële informatie dat is voortgekomen uit Microsoft's Open Financial Connectivity (OFC) en Intuit's Open Exchange bestandsformaten. Meer informatie over dit bestandsformaat vind je hier. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Onbekend bestandstype (geërfd van [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Zie ook
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
