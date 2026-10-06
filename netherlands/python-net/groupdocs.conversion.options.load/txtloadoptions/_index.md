---
title: "TxtLoadOptions klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Opties voor het laden van Txt-documenten."
type: docs
url: /nl/python-net/groupdocs.conversion.options.load/txtloadoptions/
is_root: false
weight: 500
---


## TxtLoadOptions class

Opties voor het laden van Txt-documenten.

Lettertypeconfiguratie voor platte tekst:

Aangezien TXT-bestanden geen lettertype-informatie bevatten, gebruikt u DefaultTextFont om het lettertype op te geven voor het weergeven van de platte tekstinhoud tijdens conversie.

Het type TxtLoadOptions exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/__init__/) | Initialiseert een nieuw exemplaar van [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/). |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Bepaalt of twee objectinstellingen gelijk zijn. (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Dient als de standaard hash-functie. (geërfd van [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/default_font/) | Het lettertype dat moet worden gebruikt bij het weergeven van platte tekstinhoud tijdens conversie. Standaard: Arial 10pt. |
| [detect_numbering_with_whitespaces](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/) | De eigenschap geeft aan hoe genummerde lijstitems worden herkend wanneer een platte-tekstdocument wordt geconverteerd. De standaardwaarde is True. |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/encoding/) | De codering die wordt gebruikt bij het laden van een Txt-document. Kan None zijn. Standaard is None. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/format/) | Het type invoerdocumentbestand. |
| [leading_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/leading_spaces_options/) | De voorkeursoptie voor het verwerken van voorloopspaties. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/margin_settings/) | De marge-instellingen, zoals gedefinieerd door [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/). |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/size_settings/) | De paginagrootte-opties voor het laden van een TXT-document. |
| [trailing_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/trailing_spaces_options/) | De voorkeursoptie voor het afhandelen van eindspaties. Standaardwaarde is [`TxtTrailingSpacesOptions.trim`](/conversion/python-net/groupdocs.conversion.options.load/txttrailingspacesoptions/). |

### Zie ook
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
