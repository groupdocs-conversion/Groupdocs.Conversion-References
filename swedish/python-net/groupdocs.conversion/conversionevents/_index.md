---
title: "ConversionEvents-klass"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Samlar konverteringslivscykelhändelsehanterare."
type: docs
url: /sv/python-net/groupdocs.conversion/conversionevents/
is_root: false
weight: 20
---


## ConversionEvents class

Samlar konverteringslivscykelhändelsehanterare.

Skicka en instans till [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) konstruktorns `events`-parameter eller till den flytande `WithEvents`-metoden.

Föredra detta framför de enskilda [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) hanteraregenskaperna, som är föråldrade.

ConversionEvents-typen visar följande medlemmar:

### Konstruktörer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/conversionevents/__init__/) |  |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_compression_completed/) | Händelsen som utlöses när komprimering av konverteringsutdata slutförs. Endast anropad i byggen som inkluderar komprimeringspipeline (LIB_ZIP). |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) | Händelsen som avfyras en gång när konverteringskörningen avslutas, oavsett om den lyckas eller misslyckas. |
| [on_conversion_progress](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/) | Konverteringsförloppet som en procentsats (0–100), avfyras periodiskt. |
| [on_conversion_started](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/) | Händelsen som avfyras en gång i början av konverteringskörningen, innan något dokument bearbetas. |
| [on_document_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_converted/) | Händelsen avfyras en gång per heldokumentkonvertering som slutförs framgångsrikt. |
| [on_document_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/) | Händelsen avfyras en gång per heldokumentkonvertering som misslyckas. |
| [on_font_substituted](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/) | Händelsen avfyras när ett teckensnitt som refereras av källdokumentet inte är tillgängligt och ersätts (antingen av en kundtillhandahållen [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) regel, av det konfigurerade standardteckensnittet, eller av konverteringspipelinens interna reserv). |
| [on_page_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_converted/) | Händelsen avfyras en gång per sida när en per-sida-konvertering slutförs framgångsrikt. |
| [on_page_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/) | Händelsen avfyras en gång per sida när en per-sida-konvertering misslyckas. |

### Se även
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
