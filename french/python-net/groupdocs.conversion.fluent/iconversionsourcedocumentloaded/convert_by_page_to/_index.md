---
title: "méthode convert_by_page_to"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Enregistrer la page convertie en flux."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/convert_by_page_to/
is_root: false
weight: 1010
---


## convert_by_page_to {#converted_stream_provider}

Enregistrer la page convertie en flux.

```python
def convert_by_page_to(self, converted_stream_provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| converted_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Fournisseur du flux de page de document converti converted_stream_provider arg1arg1: le contexte d'enregistrement |

**Returns:** Page options or handler setup interface to continue conversion building

### Voir aussi
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
