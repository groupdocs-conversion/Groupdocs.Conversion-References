---
title: "метод with_options"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Установить параметры конвертации."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/with_options/
is_root: false
weight: 1080
---


## with_options {#convert_options}

Установить параметры конвертации.

```python
def with_options(self, convert_options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Параметры преобразования |

**Returns:** Interface to continue conversion building

## with_options {#convert_options_provider}

Установить параметры конвертации.

```python
def with_options(self, convert_options_provider):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Параметры конвертации. `ConvertContext`. |

**Returns:** Interface to continue conversion building.

### См. также
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
