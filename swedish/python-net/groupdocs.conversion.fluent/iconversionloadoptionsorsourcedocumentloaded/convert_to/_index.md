---
title: "convert_to metod"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Spara konverterat dokument som fil."
type: docs
url: /sv/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/convert_to/
is_root: false
weight: 1030
---


## convert_to {#file_name}

Spara konverterat dokument som fil.

```python
def convert_to(self, file_name):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_name | `str` | Konverterat dokument. |

**Returns:** Options or handler setup interface to continue conversion building.

## convert_to {#converted_stream_provider}

Sparar det konverterade dokumentet som en ström.

```python
def convert_to(self, converted_stream_provider):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| converted_stream_provider | `Func[SaveContext, io.RawIOBase]` | Strömleverantör för konverterat dokument. Sparningskontexten. |

**Returns:** Options or handler setup interface to continue conversion building.

### Se även
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
