---
title: "метод with_options"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Установить параметры загрузки."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionloadoptions/with_options/
is_root: false
weight: 1010
---


## with_options {#load_options}

Установить параметры загрузки.

```python
def with_options(self, load_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| load_options | `LoadOptions` | Параметры загрузки. |

## with_options {#load_options_provider}

Предоставляет параметры загрузки для текущего загружаемого документа.

```python
def with_options(self, load_options_provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| load_options_provider | `Func[LoadContext, LoadOptions]` | Поставщик параметров загрузки. Поставщик получает контекст параметров загрузки. |

### См. также
* class [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/)
