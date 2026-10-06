---
title: "метод convert_to"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Сохранить преобразованный документ как файл."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/convert_to/
is_root: false
weight: 1030
---


## convert_to {#file_name}

Сохранить преобразованный документ как файл.

```python
def convert_to(self, file_name):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_name | `str` | Преобразованный документ. |

**Returns:** Options or handler setup interface to continue conversion building.

## convert_to {#converted_stream_provider}

Сохраняет преобразованный документ как поток.

```python
def convert_to(self, converted_stream_provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| converted_stream_provider | `Func[SaveContext, io.RawIOBase]` | Провайдер потока преобразованного документа converted_stream_provider arg1arg1: контекст сохранения |

**Returns:** Options or handler setup interface to continue conversion building

### См. также
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
