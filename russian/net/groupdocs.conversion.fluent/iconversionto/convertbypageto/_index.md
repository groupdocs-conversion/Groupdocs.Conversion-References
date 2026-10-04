---
title: "ConvertByPageTo"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Сохранить преобразованную страницу как поток"
type: docs
weight: 10
url: /ru/net/groupdocs.conversion.fluent/iconversionto/convertbypageto/
---
## IConversionTo.ConvertByPageTo method

Сохранить преобразованную страницу как поток

```csharp
public IConversionByPageOptionsOrHandlerSetup ConvertByPageTo(
    Func<SavePageContext, Stream> convertedStreamProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| convertedStreamProvider | Func`2 | Поставщик потоков страниц преобразованного документа Контекст сохранения |

### Возвращаемое значение

Параметры страницы или интерфейс настройки обработчика для продолжения построения конвертации

### См. также

* interface [IConversionByPageOptionsOrHandlerSetup](../../iconversionbypageoptionsorhandlersetup)
* class [SavePageContext](../../../groupdocs.conversion/savepagecontext)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
