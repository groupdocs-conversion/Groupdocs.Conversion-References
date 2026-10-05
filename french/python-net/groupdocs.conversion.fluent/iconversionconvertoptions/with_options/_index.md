---
title: "méthode with_options"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Définit les options de conversion."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/with_options/
is_root: false
weight: 1010
---


## with_options {#convert_options}

Définit les options de conversion.

```python
def with_options(self, convert_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Options de conversion |

**Returns:** Interface to continue conversion building

## with_options {#convert_options_provider}

Définir les options de conversion.

```python
def with_options(self, convert_options_provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Fournisseur d'options de conversion convert_options_provider arg1arg1 : le `ConvertContext` |

**Returns:** Interface to continue conversion building

### Voir aussi
* class [`IConversionConvertOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/)
