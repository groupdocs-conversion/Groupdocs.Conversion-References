---
title: "Klassen FontSubstitutionContext"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Beskriver en enskild teckensnittsersättning som inträffade vid inläsning eller rendering av ett källdokument."
type: docs
url: /sv/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/
is_root: false
weight: 190
---


## FontSubstitutionContext class

Beskriver en enskild teckensnittsersättning som inträffade vid inläsning eller rendering av ett källdokument.

Instanser skickas till [`ConversionEvents.on_font_substituted`](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/).

Typen FontSubstitutionContext exponerar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/__init__/#source_file_name-original_font_name-substitute_font_name-reason) | Initierar ett nytt FontSubstitutionContext. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [original_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) | Namnet på teckensnittet som refereras av källdokumentet men som inte är tillgängligt för konverteringspipeline. |
| [reason](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/) | Ersättningsmeddelandet exakt som rapporterats av konverteringspipeline, ordagrant och utan tolkning. |
| [source_file_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/source_file_name/) | Filnamnet på källdokumentet som konverteras. När källan tillhandahölls som en ström som inte är en `io.RawIOBase`, innehåller detta en genererad identifierare istället för ett riktigt filnamn. |
| [substitute_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/) | Namnet på teckensnittet som används som ersättning. Kan vara None för dokument vars motor rapporterar ersättningen endast som beskrivande text — i så fall läs [`FontSubstitutionContext.reason`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/). |

### Se även
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
