---
title: "метод load"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Устанавливает имя файла исходного документа."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionfrom/load/
is_root: false
weight: 1010
---


## load {#file_name}

Устанавливает имя файла исходного документа.

```python
def load(self, file_name):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_name | `str` | Исходный документ. |

## load {#file_name}

Устанавливает массив исходных документов.

```python
def load(self, file_name):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_name | `list[str]` | Набор исходных документов. |

## load {#document_stream_provider}

Установить поток исходного документа.

```python
def load(self, document_stream_provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | Поставщик потоков исходного документа. |

| Вызывает | Описание |
| :- | :- |
| `InvalidConverterSettingsException` | Если проверка параметров конвертера не удалась. |

## load {#document_stream_provider}

Устанавливает поставщика потоков исходных документов.

```python
def load(self, document_stream_provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | Поставщик потоков исходного документа. |

| Вызывает | Описание |
| :- | :- |
| `InvalidConverterSettingsException` | Если проверка параметров конвертера не удалась. |

### См. также
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
