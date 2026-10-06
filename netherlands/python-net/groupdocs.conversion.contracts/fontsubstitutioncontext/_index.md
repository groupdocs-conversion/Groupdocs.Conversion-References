---
title: "FontSubstitutionContext klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Beschrijft een enkele lettertypevervanging die optrad tijdens het laden of renderen van een brondocument."
type: docs
url: /nl/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/
is_root: false
weight: 190
---


## FontSubstitutionContext class

Beschrijft een enkele lettertypevervanging die optrad tijdens het laden of renderen van een brondocument.

Instanties worden doorgegeven aan [`ConversionEvents.on_font_substituted`](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/).

Het FontSubstitutionContext type maakt de volgende leden beschikbaar:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/__init__/#source_file_name-original_font_name-substitute_font_name-reason) | Initialiseert een nieuwe FontSubstitutionContext. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [original_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) | De naam van het lettertype dat door het brondocument wordt gerefereerd maar niet beschikbaar is voor de conversiepijplijn. |
| [reason](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/) | Het substitutiebericht precies zoals gerapporteerd door de conversiepijplijn, letterlijk en niet geparseerd. |
| [source_file_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/source_file_name/) | De bestandsnaam van het brondocument dat wordt geconverteerd. Wanneer de bron werd geleverd als een stream die geen `io.RawIOBase` is, bevat dit een gegenereerde identifier in plaats van een echte bestandsnaam. |
| [substitute_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/) | De naam van het lettertype dat als vervanging wordt gebruikt. Kan None zijn voor documenten waarvan de engine de substitutie alleen als beschrijvende tekst rapporteert — lees in dat geval [`FontSubstitutionContext.reason`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/). |

### Zie ook
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
