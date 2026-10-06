---
title: "convert_to methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Sla geconverteerd document op als bestand."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/convert_to/
is_root: false
weight: 1030
---


## convert_to {#file_name}

Sla geconverteerd document op als bestand.

```python
def convert_to(self, file_name):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_name | `str` | Geconverteerd document. |

**Returns:** Options or handler setup interface to continue conversion building.

## convert_to {#converted_stream_provider}

Slaat het geconverteerde document op als een stroom.

```python
def convert_to(self, converted_stream_provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| converted_stream_provider | `Func[SaveContext, io.RawIOBase]` | Provider van geconverteerde documentstroom converted_stream_provider arg1arg1: De opslagcontext |

**Returns:** Options or handler setup interface to continue conversion building

### Zie ook
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
