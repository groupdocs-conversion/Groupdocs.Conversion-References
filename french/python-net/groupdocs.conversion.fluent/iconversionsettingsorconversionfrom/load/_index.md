---
title: "méthode load"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Définit le nom de fichier du document source."
type: docs
url: /fr/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/load/
is_root: false
weight: 1010
---


## load {#file_name}

Définit le nom de fichier du document source.

```python
def load(self, file_name):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_name | `str` | Document source. |

## load {#file_name}

Définir le tableau de documents source.

```python
def load(self, file_name):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_name | `list[str]` | Ensemble de documents source. |

## load {#document_stream_provider}

Définir le flux du document source.

```python
def load(self, document_stream_provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | Fournisseur de flux du document source |

| Lève | Description |
| :- | :- |
| `InvalidConverterSettingsException` | Si la validation des paramètres du convertisseur échoue, cette exception sera levée |

## load {#document_stream_provider}

Définir le tableau de flux de documents source.

```python
def load(self, document_stream_provider):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | Fournisseur de flux de documents source. |

| Lève | Description |
| :- | :- |
| `InvalidConverterSettingsException` | Si la validation des paramètres du convertisseur échoue. |

### Voir aussi
* class [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/)
