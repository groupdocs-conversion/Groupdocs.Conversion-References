---
title: "FinanceFileType klass"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Definierar finansiella dokumenttyper."
type: docs
url: /sv/python-net/groupdocs.conversion.filetypes/financefiletype/
is_root: false
weight: 90
---


## FinanceFileType class

Definierar finansiella dokumenttyper.

Inkluderar följande typer: [`FinanceFileType.xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/), [`FinanceFileType.i_xbrl`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/), [`FinanceFileType.ofx`](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/). Läs mer om finansformat här: https://docs.fileformat.com/finance/.

FinanceFileType-typen exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/__init__/) | Initierar en FinanceFileType för serialisering. |

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
| [XBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/xbrl/) | XBRL är en öppen internationell standard för digital affärsrapportering som är allmänt använd globalt. Det är ett XML-baserat språk som använder XBRL-element, kända som taggar, för att beskriva varje affärsdatapunkt för att formulera data för rapportsortering och analys. Läs mer om detta filformat här. |
| [IXBRL](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ixbrl/) | I iXBRL är innehållet i XBRL inbäddat i xHTML-filformat som använder XML-taggar. Liksom XBRL är det rot-elementet i iXBRL-filer. XHTML-formatet representerar sitt innehåll som en samling av olika dokumenttyper och moduler. Alla filer i XHTML är baserade på XML-filformat och följer XML-dokumentstandarderna. Läs mer om detta filformat här. |
| [OFX](/conversion/python-net/groupdocs.conversion.filetypes/financefiletype/ofx/) | Open Financial Exchange (OFX) är ett dataflödesformat för utbyte av finansiell information som utvecklades från Microsofts Open Financial Connectivity (OFC) och Intuits Open Exchange-filformat. Läs mer om detta filformat här. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | Okänd filtyp (ärvd från [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### Se även
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
