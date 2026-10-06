---
title: "TxtLoadOptions-klass"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Alternativ för att ladda Txt-dokument."
type: docs
url: /sv/python-net/groupdocs.conversion.options.load/txtloadoptions/
is_root: false
weight: 500
---


## TxtLoadOptions class

Alternativ för att ladda Txt-dokument.

Teckensnittskonfiguration för vanlig text:

Eftersom TXT-filer inte innehåller teckensnittsinformation, använd DefaultTextFont för att ange teckensnittet för rendering av det rena textinnehållet under konvertering.

Typen TxtLoadOptions visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/__init__/) | Initierar en ny instans av [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/). |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | Bestämmer om två objektinstanser är lika. (ärvd från [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (ärvd från [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (ärvd från [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | Fungerar som standard‑hashfunktion. (ärvd från [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/default_font/) | Teckensnittet som ska användas vid rendering av rent textinnehåll under konvertering. Standard: Arial 10pt. |
| [detect_numbering_with_whitespaces](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/) | Egenskapen anger hur numrerade listobjekt identifieras när ett rent textdokument konverteras. Standardvärdet är True. |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/encoding/) | Kodningen som används när ett Txt-dokument laddas. Kan vara None. Standard är None. |
| [format](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/format/) | Inmatningsdokumentets filtyp. |
| [leading_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/leading_spaces_options/) | Det föredragna alternativet för hantering av inledande mellanslag. |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/margin_settings/) | Marginalinställningarna, enligt definitionen i [`IPageMarginOptions`](/conversion/python-net/groupdocs.conversion.options/ipagemarginoptions/). |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/size_settings/) | Sidstorleksalternativen för att ladda ett TXT-dokument. |
| [trailing_spaces_options](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/trailing_spaces_options/) | Det föredragna alternativet för hantering av avslutande mellanslag. Standardvärdet är [`TxtTrailingSpacesOptions.trim`](/conversion/python-net/groupdocs.conversion.options.load/txttrailingspacesoptions/). |

### Se även
* module [`groupdocs.conversion.options.load`](/conversion/python-net/groupdocs.conversion.options.load/)
