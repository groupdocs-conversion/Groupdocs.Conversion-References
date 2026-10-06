---
title: "IConversionHandlersStage klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Stelt een afgevlakte conversie‑handlers fase voor."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/
is_root: false
weight: 270
---


## IConversionHandlersStage class

Stelt een afgevlakte conversie‑handlers fase voor.

Staat toe om `OnConversionCompleted` of `OnConversionFailed` in willekeurige volgorde en onbeperkt vaak in te stellen, vóór doorgaan naar `Convert` / `Compress`. Events moeten vroeg in de fase worden geregistreerd via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) in plaats van in deze fase.

Het type IConversionHandlersStage exposeert de volgende leden:

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress/#options) | Comprimeert de conversieresultaten. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/convert/) | Voer conversieketen uit. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/#on_completed) | Registreert een callback die wordt aangeroepen wanneer een documentconversie succesvol wordt voltooid, en vervangt elke eerder ingestelde handler bij heraanroep. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed/#on_failed) | Registreert een callback die wordt aangeroepen wanneer een documentconversie mislukt. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed_action/) |  |

### Zie ook
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
