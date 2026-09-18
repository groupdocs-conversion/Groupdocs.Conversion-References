---
title: ConversionEvents class
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Aggregates conversion lifecycle event handlers."
type: docs
url: /python-net/groupdocs.conversion/conversionevents/
is_root: false
weight: 20
---


## ConversionEvents class

Aggregates conversion lifecycle event handlers.

Pass an instance to the [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) constructor's `events` parameter or to the fluent `WithEvents` method.

Prefer this over the individual [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/) handler properties, which are obsolete.

The ConversionEvents type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/conversionevents/__init__/) |  |

### Properties
| Property | Description |
| :- | :- |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_compression_completed/) | The event that is fired when compression of conversion output completes. Only invoked in builds that include the compression pipeline (LIB_ZIP). |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) | The event that fires once when the conversion run finishes, regardless of success or failure. |
| [on_conversion_progress](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/) | The conversion progress as a percentage (0–100), fired periodically. |
| [on_conversion_started](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/) | The event that is fired once at the start of the conversion run, before any document is processed. |
| [on_document_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_converted/) | The event is fired once per whole-document conversion that completes successfully. |
| [on_document_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/) | The event fired once per whole-document conversion that fails. |
| [on_font_substituted](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/) | The event fired when a font referenced by the source document is not available and is substituted (either by a customer‑supplied [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) rule, by the configured default font, or by the conversion pipeline's internal fallback). |
| [on_page_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_converted/) | The event fired once per page when a per-page conversion completes successfully. |
| [on_page_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/) | The event fired once per page when a per-page conversion fails. |

### See Also
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
