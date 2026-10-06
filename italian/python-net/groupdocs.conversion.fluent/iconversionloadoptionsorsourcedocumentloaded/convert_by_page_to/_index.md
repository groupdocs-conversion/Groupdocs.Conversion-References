---
title: "Metodo convert_by_page_to"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Salva la pagina convertita come stream."
type: docs
url: /it/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/convert_by_page_to/
is_root: false
weight: 1010
---


## convert_by_page_to {#converted_stream_provider}

Salva la pagina convertita come stream.

```python
def convert_by_page_to(self, converted_stream_provider):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| converted_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Provider dello stream della pagina del documento convertito. |

**Returns:** Page options or handler setup interface to continue conversion building.

### Vedi anche
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
