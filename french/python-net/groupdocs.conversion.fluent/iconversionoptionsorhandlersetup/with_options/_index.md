---
title: "méthode with_options"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Définit les options de conversion pour le processus de conversion."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/with_options/
is_root: false
weight: 1080
---


## with_options {#convert_options}

Définit les options de conversion pour le processus de conversion.

```python
def with_options(self, convert_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Options de conversion. |

**Returns:** Handler setup interface to continue conversion building.

## with_options {#options_provider}

Définit les options de conversion en utilisant une fonction fournisseur.

```python
def with_options(self, options_provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options_provider | `Func[ConvertContext, ConvertOptions]` | Une fonction qui fournit les options de conversion en fonction du contexte de conversion. |

**Returns:** Handler setup interface to continue conversion building.

### Voir aussi
* class [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/)
