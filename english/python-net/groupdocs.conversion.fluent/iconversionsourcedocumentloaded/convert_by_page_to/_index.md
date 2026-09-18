---
title: convert_by_page_to method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Save converted page as stream."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/convert_by_page_to/
is_root: false
weight: 1010
---


## convert_by_page_to {#converted_stream_provider}

Save converted page as stream.

```python
def convert_by_page_to(self, converted_stream_provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| converted_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Converted document page stream provider converted_stream_provider arg1arg1: The save context |

**Returns:** Page options or handler setup interface to continue conversion building

### See Also
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
