---
title: "WithOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Установить параметры конвертации"
type: docs
weight: 10
url: /ru/net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Установить параметры конвертации

```csharp
public IConversionByPageHandlersStage WithOptions(ConvertOptions convertOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| convertOptions | ConvertOptions | Параметры конвертации |

### Возвращаемое значение

Интерфейс для продолжения построения конвертации

### См. также

* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertByPageOptions](../../iconversionconvertbypageoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

Установить параметры конвертации

```csharp
public IConversionByPageHandlersStage WithOptions(
    Func<ConvertContext, ConvertOptions> convertOptionsProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Параметры преобразования [`ConvertContext`](../../../groupdocs.conversion/convertcontext) |

### Возвращаемое значение

Интерфейс для продолжения построения конвертации

### См. также

* interface [IConversionByPageHandlersStage](../../iconversionbypagehandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertByPageOptions](../../iconversionconvertbypageoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
