---
title: "метод with_options"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Устанавливает параметры конвертации для процесса конвертации."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/with_options/
is_root: false
weight: 1010
---


## with_options {#convert_options}

Устанавливает параметры конвертации для процесса конвертации.

```python
def with_options(self, convert_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Параметры конверсии. |

**Returns:** Handler setup interface to continue conversion building.

## with_options {#options_provider}

Устанавливает параметры конвертации с помощью функции‑поставщика.

```python
def with_options(self, options_provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| options_provider | `Func[ConvertContext, ConvertOptions]` | Функция, которая предоставляет параметры конверсии на основе контекста конверсии. |

**Returns:** Handler setup interface to continue conversion building.

### См. также
* class [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/)
