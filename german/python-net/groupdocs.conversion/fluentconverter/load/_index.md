---
title: "load Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Quellendokument für die Konvertierung konfigurieren."
type: docs
url: /de/python-net/groupdocs.conversion/fluentconverter/load/
is_root: false
weight: 1010
---


## load {#file_name}

Quellendokument für die Konvertierung konfigurieren.

```python
def load(cls, file_name):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_name | `str` | Quelldokument. |

## load {#file_name}

Satz von Quellendokumenten konfigurieren.

```python
def load(cls, file_name):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_name | `list[str]` | Array von Quelldateien. |

## load {#document_stream_provider}

Quellendokument-Stream konfigurieren.

```python
def load(cls, document_stream_provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | Anbieter für Quelldokument-Stream. |

## load {#document_stream_provider}

Satz von Quellendokument-Streams konfigurieren.

```python
def load(cls, document_stream_provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | Menge von Anbietern für Quell‑Dokument‑Streams. |

### Siehe auch
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
