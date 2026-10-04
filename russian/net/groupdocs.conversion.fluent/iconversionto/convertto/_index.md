---
title: "ConvertTo"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Сохранить преобразованный документ как файл"
type: docs
weight: 20
url: /ru/net/groupdocs.conversion.fluent/iconversionto/convertto/
---
## ConvertTo(string) {#convertto_1}

Сохранить преобразованный документ как файл

```csharp
public IConversionOptionsOrHandlerSetup ConvertTo(string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Преобразованный документ |

### Возвращаемое значение

Параметры или интерфейс настройки обработчика для продолжения построения конвертации

### См. также

* interface [IConversionOptionsOrHandlerSetup](../../iconversionoptionsorhandlersetup)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## ConvertTo(Func&lt;SaveContext, Stream&gt;) {#convertto}

Сохранить преобразованный документ как поток

```csharp
public IConversionOptionsOrHandlerSetup ConvertTo(Func<SaveContext, Stream> convertedStreamProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| convertedStreamProvider | Func`2 | Поставщик потоков преобразованного документа Контекст сохранения |

### Возвращаемое значение

Параметры или интерфейс настройки обработчика для продолжения построения конвертации

### См. также

* interface [IConversionOptionsOrHandlerSetup](../../iconversionoptionsorhandlersetup)
* class [SaveContext](../../../groupdocs.conversion/savecontext)
* interface [IConversionTo](../../iconversionto)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
