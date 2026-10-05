---
title: "méthode convert_to"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Enregistrer le document converti en fichier."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/convert_to/
is_root: false
weight: 1030
---


## convert_to {#file_name}

Enregistrer le document converti en fichier.

```python
def convert_to(self, file_name):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_name | `str` | Document converti. |

**Returns:** Options or handler setup interface to continue conversion building.

## convert_to {#converted_stream_provider}

Enregistre le document converti en flux.

```python
def convert_to(self, converted_stream_provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| converted_stream_provider | `Func[SaveContext, io.RawIOBase]` | Fournisseur de flux du document converti. Le contexte d'enregistrement. |

**Returns:** Options or handler setup interface to continue conversion building.

### Voir aussi
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
