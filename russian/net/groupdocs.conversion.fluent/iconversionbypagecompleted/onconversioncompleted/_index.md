---
title: OnConversionCompleted
second_title: Справочник по API GroupDocs.Conversion для .NET
description: Получить преобразованный поток страниц. Будет запущено только если установлено Сохранить SaveDocumentStreamForFileType.
type: docs
weight: 10
url: /ru/net/groupdocs.conversion.fluent/iconversionbypagecompleted/onconversioncompleted/
---
## IConversionByPageCompleted.OnConversionCompleted method

Получить преобразованный поток страниц. Будет запущено, только если установлено «Сохранить (SaveDocumentStreamForFileType)».

```csharp
public IConversionConvertOrCompress OnConversionCompleted(ConvertedPageStream convertedPageStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| convertedPageStream | ConvertedPageStream | Поставщик потока преобразованных страниц |

### Возвращаемое значение

Интерфейс для продолжения построения конверсии

### Смотрите также

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* interface [IConversionByPageCompleted](../../iconversionbypagecompleted)
* пространство имен [GroupDocs.Conversion.Fluent](../../iconversionbypagecompleted)
* сборка [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
