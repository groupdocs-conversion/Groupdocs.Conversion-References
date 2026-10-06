---
title: "convert_by_page_to methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Sla geconverteerde pagina op als stream."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/convert_by_page_to/
is_root: false
weight: 1010
---


## convert_by_page_to {#converted_stream_provider}

Sla geconverteerde pagina op als stream.

```python
def convert_by_page_to(self, converted_stream_provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| converted_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Provider van geconverteerde documentpagina-stroom converted_stream_provider arg1arg1: De opslagcontext |

**Returns:** Page options or handler setup interface to continue conversion building

### Zie ook
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
