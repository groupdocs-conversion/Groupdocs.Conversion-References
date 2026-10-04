---
title: "GetDocumentInfo"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Получает информацию исходного документа, количество страниц и другие свойства документа, специфичные для типа файла."
type: docs
weight: 40
url: /ru/net/groupdocs.conversion/converter/getdocumentinfo/
---
## GetDocumentInfo() {#getdocumentinfo}

Получает информацию о исходном документе — количество страниц и другие свойства документа, специфичные для типа файла.

```csharp
public IDocumentInfo GetDocumentInfo()
```

### Возвращаемое значение

Информация о документе как [`IDocumentInfo`](../../../groupdocs.conversion.contracts/idocumentinfo).

### Примечания

**Learn more**

* Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info](https://docs.groupdocs.com/display/conversionnet/Get+document+info)

### См. также

* interface [IDocumentInfo](../../../groupdocs.conversion.contracts/idocumentinfo)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## GetDocumentInfo&lt;T&gt;() {#getdocumentinfo_1}

Получает информацию о исходном документе — количество страниц и другие свойства документа, специфичные для типа файла.

```csharp
public T GetDocumentInfo<T>()
    where T : IDocumentInfo
```

| Параметр | Описание |
| --- | --- |
| T | Конкретный тип информации о документе. |

### Возвращаемое значение

Информация о документе как указанный тип T.

### Примечания

**Learn more**

* Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info](https://docs.groupdocs.com/display/conversionnet/Get+document+info)

### См. также

* interface [IDocumentInfo](../../../groupdocs.conversion.contracts/idocumentinfo)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
