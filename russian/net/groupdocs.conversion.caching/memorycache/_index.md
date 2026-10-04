---
title: "MemoryCache"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Поведение кэширования в памяти. Означает, что кэш хранится в памяти"
type: docs
weight: 30
url: /ru/net/groupdocs.conversion.caching/memorycache/
---
## MemoryCache class

Поведение кэширования в памяти. Означает, что кэш хранится в памяти

```csharp
public sealed class MemoryCache : ICache
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [MemoryCache](memorycache)() | Создаёт новый экземпляр класса MemoryCache |

## Методы

| Имя | Описание |
| --- | --- |
| [GetKeys](../../groupdocs.conversion.caching/memorycache/getkeys)(string) | Возвращает все ключи, соответствующие фильтру. |
| [Set](../../groupdocs.conversion.caching/memorycache/set)(string, object) | Вставляет запись в кэш. |
| [TryGetValue](../../groupdocs.conversion.caching/memorycache/trygetvalue)(string, out object) | Получает запись, связанную с этим ключом, если она присутствует. |

### Примечания

**Learn more**

* More about caching and optimizing conversion process performance: [Caching conversion results](https://docs.groupdocs.com/display/conversionnet/Caching)

### См. также

* interface [ICache](../icache)
* namespace [GroupDocs.Conversion.Caching](../../groupdocs.conversion.caching)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
