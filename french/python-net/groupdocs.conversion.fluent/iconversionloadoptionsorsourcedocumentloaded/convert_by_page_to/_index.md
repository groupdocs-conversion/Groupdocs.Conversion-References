---
title: "méthode convert_by_page_to"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Enregistre la page convertie sous forme de flux."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/convert_by_page_to/
is_root: false
weight: 1010
---


## convert_by_page_to {#converted_stream_provider}

Enregistre la page convertie sous forme de flux.

```python
def convert_by_page_to(self, converted_stream_provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| converted_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Fournisseur de flux de page de document converti. |

**Returns:** Page options or handler setup interface to continue conversion building.

### Voir aussi
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
