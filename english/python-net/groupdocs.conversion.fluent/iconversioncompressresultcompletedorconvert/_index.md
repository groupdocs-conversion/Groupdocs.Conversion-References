---
title: IConversionCompressResultCompletedOrConvert class
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Continuation after Compress(...)."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/
is_root: false
weight: 130
---


## IConversionCompressResultCompletedOrConvert class

Continuation after `Compress(...)`. Proceed directly with `Convert`; the inherited [`IConversionCompressResultCompleted.OnCompressionCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompleted/on_compression_completed/) is obsolete — register the handler at the entry stage via [`IConversionSettings.WithEvents`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) instead.

The IConversionCompressResultCompletedOrConvert type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [convert](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/convert/) | Execute conversion chain. |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/on_compression_completed/#compressed_document_stream) | Receives a compressed document stream. Fires only if `Compress(CompressionConvertOptions)` is set. |
| [on_compression_completed_action](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompressresultcompletedorconvert/on_compression_completed_action/) |  |

### See Also
* module [`groupdocs.conversion.fluent`](/conversion/python-net/groupdocs.conversion.fluent/)
