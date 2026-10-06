---
title: "IConversionByPageHandlerOnly-klass"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Tillhandahåller ett flytande gränssnitt för att endast ställa in per-sida konverteringshanterare."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/
is_root: false
weight: 50
---


## IConversionByPageHandlerOnly class

Tillhandahåller ett flytande gränssnitt för att endast ställa in per-sida konverteringshanterare.

Ärver [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) för `Convert`/`Compress`; de staged `OnConversion*`-överladdningarna behålls via nyckelordet `new` för att bevara bakåtkompatibilitet.

Typen IConversionByPageHandlerOnly exponerar följande medlemmar:

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/#options) | Komprimerar konverteringsresultaten; registrera en komprimerad‑strömshanterare i ingångsstadiet via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (sätter `OnCompressionCompleted`) istället för att använda den föråldrade flytande kedjemetoden. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/convert/) | Utför konverteringskedjan. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed/#on_completed) | Registrerar en återuppringning som ska anropas när en sidkonvertering slutförs framgångsrikt. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed/#on_failed) | Registrerar en återuppringning som ska anropas när en sidkonvertering misslyckas. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed_action/) |  |

### Se även
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
