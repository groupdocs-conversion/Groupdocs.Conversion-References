---
title: "with_options-methode"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Stel laadopties in."
type: docs
url: /nl/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/with_options/
is_root: false
weight: 1100
---


## with_options {#load_options}

Stel laadopties in.

```python
def with_options(self, load_options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| load_options | `LoadOptions` | Laadopties |

## with_options {#load_options_provider}

Biedt laadopties voor het document dat momenteel wordt geladen.

```python
def with_options(self, load_options_provider):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| load_options_provider | `Func[LoadContext, LoadOptions]` | Provider van laadopties. De context van laadopties. |

### Zie ook
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
