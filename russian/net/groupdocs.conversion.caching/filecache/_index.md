---
title: "FileCache"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Поведение кэширования файлов. Означает, что кэш хранится в файловой системе"
type: docs
weight: 10
url: /ru/net/groupdocs.conversion.caching/filecache/
---
## FileCache class

Поведение кэширования файлов. Означает, что кэш хранится в файловой системе

```csharp
public sealed class FileCache : ICache
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FileCache](filecache)(string) | Создаёт новый экземпляр класса FileCache |

## Методы

| Имя | Описание |
| --- | --- |
| [GetKeys](../../groupdocs.conversion.caching/filecache/getkeys)(string) | Возвращает все ключи, соответствующие фильтру. |
| [Set](../../groupdocs.conversion.caching/filecache/set)(string, object) | Вставляет запись в кэш. |
| [TryGetValue](../../groupdocs.conversion.caching/filecache/trygetvalue)(string, out object) | Получает запись, связанную с этим ключом, если она присутствует. |

### Примечания

**Learn more**

* More about caching and optimizing conversion process performance: [Caching conversion results](https://docs.groupdocs.com/display/conversionnet/Caching)

### См. также

* interface [ICache](../icache)
* namespace [GroupDocs.Conversion.Caching](../../groupdocs.conversion.caching)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
