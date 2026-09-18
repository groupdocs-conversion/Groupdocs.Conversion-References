---
title: compress method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Compresses the conversion results; register a compressed‑stream handler at the entry stage via IConversionSettings.withevents (setting OnCompressionCompleted) instead of using the obsolete fluent…"
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/
is_root: false
weight: 1010
---


## compress {#options}

Compresses the conversion results; register a compressed‑stream handler at the entry stage via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (setting `OnCompressionCompleted`) instead of using the obsolete fluent chain method.

```python
def compress(self, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Compression convert options. |

**Returns:** Continuation that proceeds to `Convert`.

### See Also
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
