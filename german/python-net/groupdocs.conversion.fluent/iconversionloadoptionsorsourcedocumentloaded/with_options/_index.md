---
title: "with_options Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Ladeoptionen festlegen."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/with_options/
is_root: false
weight: 1100
---


## with_options {#load_options}

Ladeoptionen festlegen.

```python
def with_options(self, load_options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| load_options | `LoadOptions` | Ladeoptionen |

## with_options {#load_options_provider}

Stellt Ladeoptionen für das aktuell geladene Dokument bereit.

```python
def with_options(self, load_options_provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| load_options_provider | `Func[LoadContext, LoadOptions]` | Ladeoptionen-Provider. Der Kontext der Ladeoptionen. |

### Siehe auch
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
