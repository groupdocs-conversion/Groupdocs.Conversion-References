---
title: convert_to method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Save converted document as file."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionto/convert_to/
is_root: false
weight: 1030
---


## convert_to {#file_name}

Save converted document as file.

```python
def convert_to(self, file_name):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_name | `str` | Converted document |

**Returns:** Options or handler setup interface to continue conversion building

## convert_to {#converted_stream_provider}

Saves the converted document as a stream.

```python
def convert_to(self, converted_stream_provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| converted_stream_provider | `Func[SaveContext, io.RawIOBase]` | Converted document stream provider. The save context. |

**Returns:** Options or handler setup interface to continue conversion building.

### See Also
* class [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/)
