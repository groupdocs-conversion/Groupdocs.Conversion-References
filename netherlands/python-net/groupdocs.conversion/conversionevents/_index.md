---
title: "ConversionEvents klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Aggregeert gebeurtenishandlers voor de levenscyclus van conversie."
type: docs
url: /nl/python-net/groupdocs.conversion/conversionevents/
is_root: false
weight: 20
---


## ConversionEvents class

Aggregeert gebeurtenishandlers voor de levenscyclus van conversie.

Geef een instantie door aan de constructor van [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) `events`‑parameter of aan de fluent‑methode `WithEvents`.

Geef de voorkeur aan dit boven de individuele handler‑eigenschappen van [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/), die verouderd zijn.

Het ConversionEvents-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/conversionevents/__init__/) |  |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_compression_completed/) | De gebeurtenis die wordt geactiveerd wanneer de compressie van de conversie‑output voltooid is. Alleen aangeroepen in builds die de compressiepijplijn (LIB_ZIP) bevatten. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) | Het evenement dat één keer wordt geactiveerd wanneer de conversierun eindigt, ongeacht of deze slaagt of faalt. |
| [on_conversion_progress](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/) | De voortgang van de conversie als een percentage (0–100), periodiek geactiveerd. |
| [on_conversion_started](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/) | Het evenement dat één keer wordt geactiveerd aan het begin van de conversierun, voordat een document wordt verwerkt. |
| [on_document_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_converted/) | Het evenement wordt één keer geactiveerd per volledige documentconversie die succesvol wordt voltooid. |
| [on_document_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/) | Het evenement wordt één keer geactiveerd per volledige documentconversie die faalt. |
| [on_font_substituted](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/) | Het evenement wordt geactiveerd wanneer een lettertype dat door het brondocument wordt gerefereerd niet beschikbaar is en wordt vervangen (ofwel door een door de klant geleverde [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) regel, door het geconfigureerde standaardlettertype, of door de interne fallback van de conversiepijplijn). |
| [on_page_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_converted/) | Het evenement wordt één keer per pagina geactiveerd wanneer een per-pagina conversie succesvol wordt voltooid. |
| [on_page_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/) | Het evenement wordt één keer per pagina geactiveerd wanneer een per-pagina conversie faalt. |

### Zie ook
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
