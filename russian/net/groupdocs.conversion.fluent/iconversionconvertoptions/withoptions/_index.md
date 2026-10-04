---
title: "WithOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Установить параметры конвертации"
type: docs
weight: 10
url: /ru/net/groupdocs.conversion.fluent/iconversionconvertoptions/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Установить параметры конвертации

```csharp
public IConversionHandlersStage WithOptions(ConvertOptions convertOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| convertOptions | ConvertOptions | Параметры конвертации |

### Возвращаемое значение

Интерфейс для продолжения построения конвертации

### См. также

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertOptions](../../iconversionconvertoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

Установить параметры конвертации

```csharp
public IConversionHandlersStage WithOptions(
    Func<ConvertContext, ConvertOptions> convertOptionsProvider)
```

| Параметр | Описание |
| --- | --- |
| convertOptionsProvider | Поставщик параметров конвертации |
| convertOptionsProvider arg1arg1 | [`ConvertContext`](../../../groupdocs.conversion/convertcontext) |

### Возвращаемое значение

Интерфейс для продолжения построения конвертации

### См. также

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionConvertOptions](../../iconversionconvertoptions)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
