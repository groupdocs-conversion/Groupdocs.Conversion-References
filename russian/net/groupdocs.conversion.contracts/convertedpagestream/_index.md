---
title: ConvertedPageStream
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Описывает делегат для получения преобразованного потока страниц документа.
type: docs
weight: 120
url: /ru/net/groupdocs.conversion.contracts/convertedpagestream/
---
## ConvertedPageStream delegate

Описывает делегат для получения преобразованного потока страниц документа.

```csharp
public delegate void ConvertedPageStream(int pageNumber, Stream stream, string sourceFileName);
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | Int32 | Преобразованный номер страницы |
| stream | Stream | Поток преобразованных страниц |
| sourceFileName | String | Имя преобразованного документа |

### Смотрите также

* пространство имен [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* сборка [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
