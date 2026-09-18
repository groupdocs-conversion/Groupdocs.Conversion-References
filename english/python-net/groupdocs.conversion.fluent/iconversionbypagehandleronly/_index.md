---
title: IConversionByPageHandlerOnly class
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Provides a fluent interface for setting only by-page conversion handlers."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/
is_root: false
weight: 50
---


## IConversionByPageHandlerOnly class

Provides a fluent interface for setting only by-page conversion handlers.

Inherits [`IConversionByPageHandlersStage`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlersstage/) for `Convert`/`Compress`; the staged `OnConversion*` overloads are kept via the `new` keyword to preserve back compatibility.

The IConversionByPageHandlerOnly type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/#options) | Compresses the conversion results; register a compressed‑stream handler at the entry stage via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (setting `OnCompressionCompleted`) instead of using the obsolete fluent chain method. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/convert/) | Execute conversion chain. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed/#on_completed) | Registers a callback to be invoked when a page conversion completes successfully. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed/#on_failed) | Registers a callback to be invoked when a page conversion fails. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed_action/) |  |

### See Also
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
