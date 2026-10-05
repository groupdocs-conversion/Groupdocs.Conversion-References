---
title: "méthode load"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Configurer le document source pour la conversion."
type: docs
url: /fr/python-net/groupdocs.conversion/fluentconverter/load/
is_root: false
weight: 1010
---


## load {#file_name}

Configurer le document source pour la conversion.

```python
def load(cls, file_name):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_name | `str` | Document source. |

## load {#file_name}

Configurer l’ensemble de documents sources.

```python
def load(cls, file_name):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_name | `list[str]` | Tableau de fichiers source. |

## load {#document_stream_provider}

Configurer le flux du document source.

```python
def load(cls, document_stream_provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | Fournisseur de flux de document source. |

## load {#document_stream_provider}

Configurer un ensemble de flux de documents sources.

```python
def load(cls, document_stream_provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | Ensemble du fournisseur de flux de documents source. |

### Voir aussi
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
