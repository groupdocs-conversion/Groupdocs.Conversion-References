---
title: "IConversionByPageHandlerOnly klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Biedt een vloeiende interface voor het instellen van alleen per-pagina conversie‑handlers."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/
is_root: false
weight: 50
---


## IConversionByPageHandlerOnly class

Biedt een vloeiende interface voor het instellen van alleen per-pagina conversie‑handlers.

Erft [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) voor `Convert`/`Compress`; de gestage `OnConversion*` overloads worden behouden via het `new` keyword om terugwaartse compatibiliteit te behouden.

Het type IConversionByPageHandlerOnly exposeert de volgende leden:

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/#options) | Comprimeert de conversieresultaten; registreer een gecomprimeerde‑stream handler in de instapfase via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (instellen van `OnCompressionCompleted`) in plaats van de verouderde vloeiende ketenmethode te gebruiken. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/convert/) | Voer conversieketen uit. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed/#on_completed) | Registreert een callback die wordt aangeroepen wanneer een paginaconversie succesvol wordt voltooid. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed/#on_failed) | Registreert een callback die wordt aangeroepen wanneer een paginaconversie mislukt. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed_action/) |  |

### Zie ook
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
