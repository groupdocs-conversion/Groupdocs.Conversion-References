---
title: "méthode with_options"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Définir les options de chargement."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionloadoptions/with_options/
is_root: false
weight: 1010
---


## with_options {#load_options}

Définir les options de chargement.

```python
def with_options(self, load_options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| load_options | `LoadOptions` | Options de chargement. |

## with_options {#load_options_provider}

Fournit les options de chargement pour le document en cours de chargement.

```python
def with_options(self, load_options_provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| load_options_provider | `Func[LoadContext, LoadOptions]` | Fournisseur d'options de chargement. Le fournisseur reçoit le contexte des options de chargement. |

### Voir aussi
* class [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/)
