---
title: "load Methode"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Setzt den Dateinamen des Quelldokuments."
type: docs
url: /de/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/load/
is_root: false
weight: 1010
---


## load {#file_name}

Setzt den Dateinamen des Quelldokuments.

```python
def load(self, file_name):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_name | `str` | Quelldokument. |

## load {#file_name}

Setze das Quell-Dokument-Array.

```python
def load(self, file_name):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_name | `list[str]` | Menge von Quelldokumenten. |

## load {#document_stream_provider}

Quelldokument-Stream festlegen.

```python
def load(self, document_stream_provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | Anbieter des Quelldokumenten‑Streams |

| Wirft | Beschreibung |
| :- | :- |
| `InvalidConverterSettingsException` | Wenn die Validierung der Konverter‑Einstellungen fehlschlägt, wird diese Ausnahme ausgelöst. |

## load {#document_stream_provider}

Setze das Quell-Dokument-Stream-Array.

```python
def load(self, document_stream_provider):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | Anbieter für Quelldokument-Streams. |

| Wirft | Beschreibung |
| :- | :- |
| `InvalidConverterSettingsException` | Falls die Validierung der Konverter‑Einstellungen fehlschlägt. |

### Siehe auch
* class [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/)
