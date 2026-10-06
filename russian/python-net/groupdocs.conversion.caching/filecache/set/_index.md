---
title: "метод set"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Вставляет запись в кэш."
type: docs
url: /ru/python-net/groupdocs.conversion.caching/filecache/set/
is_root: false
weight: 1040
---


## set {#key-value}

Вставляет запись в кэш.

```python
def set(self, key, value):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | `str` | Уникальный идентификатор для записи кэша. |
| value | `Any` | Объект для вставки. |

### Пример

```python
from groupdocs.conversion import ConverterSettings, FileCache

# Создать настройки конвертера с файловым кэшем
settings = ConverterSettings()
settings.cache = FileCache()

# Сохранить объект в кэше
settings.cache.set("my_document", document)
```

### См. также
* class [`FileCache`](/conversion/python-net/groupdocs.conversion.caching/filecache/)
