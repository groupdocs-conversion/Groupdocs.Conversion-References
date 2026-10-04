---
title: "WithOptions"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Устанавливает параметры конвертации для процесса конверсии."
type: docs
weight: 10
url: /ru/net/groupdocs.conversion.fluent/iconversionoptionsonly/withoptions/
---
## WithOptions(ConvertOptions) {#withoptions}

Устанавливает параметры конвертации для процесса конверсии.

```csharp
public IConversionHandlersStage WithOptions(ConvertOptions convertOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| convertOptions | ConvertOptions | Параметры конвертации. |

### Возвращаемое значение

Этап обработчиков для продолжения построения конвертации.

### См. также

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionOptionsOnly](../../iconversionoptionsonly)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## WithOptions(Func&lt;ConvertContext, ConvertOptions&gt;) {#withoptions_1}

Устанавливает параметры конвертации с помощью функции‑поставщика.

```csharp
public IConversionHandlersStage WithOptions(Func<ConvertContext, ConvertOptions> optionsProvider)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| optionsProvider | Func`2 | Функция, предоставляющая параметры конвертации на основе контекста конвертации. |

### Возвращаемое значение

Этап обработчиков для продолжения построения конвертации.

### См. также

* interface [IConversionHandlersStage](../../iconversionhandlersstage)
* class [ConvertContext](../../../groupdocs.conversion/convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* interface [IConversionOptionsOnly](../../iconversionoptionsonly)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
