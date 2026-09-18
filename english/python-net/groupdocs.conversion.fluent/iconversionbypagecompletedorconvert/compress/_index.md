---
title: compress method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Compresses the conversion results."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/compress/
is_root: false
weight: 1010
---


## compress {#options}

Compresses the conversion results.

Register a compressed‑stream handler at the entry stage via [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (setting `OnCompressionCompleted`) rather than via the obsolete fluent chain method on the returned interface.

```python
def compress(self, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | `CompressionConvertOptions` | Compression convert options. |

**Returns:** Continuation that proceeds to `Convert`.

### See Also
* class [`IConversionByPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagecompletedorconvert/)
