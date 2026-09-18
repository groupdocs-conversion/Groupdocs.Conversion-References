---
title: convert_by_page_to method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Saves the converted page as a stream."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/convert_by_page_to/
is_root: false
weight: 1010
---


## convert_by_page_to {#converted_stream_provider}

Saves the converted page as a stream.

```python
def convert_by_page_to(self, converted_stream_provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| converted_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Converted document page stream provider. |

**Returns:** Page options or handler setup interface to continue conversion building.

### See Also
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
