---
title: "метод load"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Настройте исходный документ для конвертации."
type: docs
url: /ru/python-net/groupdocs.conversion/fluentconverter/load/
is_root: false
weight: 1010
---


## load {#file_name}

Настройте исходный документ для конвертации.

```python
def load(cls, file_name):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_name | `str` | Исходный документ. |

## load {#file_name}

Настройте набор исходных документов.

```python
def load(cls, file_name):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_name | `list[str]` | Массив исходных файлов. |

## load {#document_stream_provider}

Настройте поток исходного документа.

```python
def load(cls, document_stream_provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | Поставщик потоков исходного документа. |

## load {#document_stream_provider}

Настройте набор потоков исходных документов.

```python
def load(cls, document_stream_provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | Набор поставщика потоков исходных документов. |

### См. также
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
