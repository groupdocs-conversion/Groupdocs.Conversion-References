---
title: "IConversionHandlersStage-klass"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Representerar ett plattat steg för konverteringshanterare."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/
is_root: false
weight: 270
---


## IConversionHandlersStage class

Representerar ett plattat steg för konverteringshanterare.

Tillåter att ställa in `OnConversionCompleted` eller `OnConversionFailed` i vilken ordning och hur många gånger som helst, innan man fortsätter till `Convert` / `Compress`. Händelser bör registreras i ett tidigt stadium via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) istället för i detta stadium.

Typen IConversionHandlersStage exponerar följande medlemmar:

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress/#options) | Komprimerar konverteringsresultaten. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/convert/) | Utför konverteringskedjan. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/#on_completed) | Registrerar en återuppringning som ska anropas när en dokumentkonvertering slutförs framgångsrikt, och ersätter tidigare inställd hanterare vid återanrop. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed/#on_failed) | Registrerar en återuppringning som ska anropas när en dokumentkonvertering misslyckas. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed_action/) |  |

### Se även
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
