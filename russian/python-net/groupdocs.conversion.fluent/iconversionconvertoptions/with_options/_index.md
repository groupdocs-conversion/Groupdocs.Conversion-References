---
title: "метод with_options"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Устанавливает параметры конвертации."
type: docs
url: /ru/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/with_options/
is_root: false
weight: 1010
---


## with_options {#convert_options}

Устанавливает параметры конвертации.

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
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Поставщик параметров преобразования convert_options_provider arg1arg1: `ConvertContext` |

**Returns:** Interface to continue conversion building

### См. также
* class [`IConversionConvertOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptions/)
