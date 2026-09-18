---
title: IConversionHandlersStage class
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Represents a flattened conversion handlers stage."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionhandlersstage/
is_root: false
weight: 270
---


## IConversionHandlersStage class

Represents a flattened conversion handlers stage.

Allows setting `OnConversionCompleted` or `OnConversionFailed` in any order and any number of times, before proceeding to `Convert` / `Compress`. Events should be registered at the early stage via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) instead of in this stage.

The IConversionHandlersStage type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [compress](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress/#options) | Compresses the conversion results. |
| [compress_compression_convert_options](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/compress_compression_convert_options/) |  |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/convert/) | Execute conversion chain. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed/#on_completed) | Registers a callback to be invoked when a document conversion completes successfully, replacing any previously set handler on re‑invocation. |
| [on_conversion_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_completed_action/) |  |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed/#on_failed) | Registers a callback to be invoked when a document conversion fails. |
| [on_conversion_failed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlersstage/on_conversion_failed_action/) |  |

### See Also
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
