---
title: "OnFontSubstituted"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Срабатывает, когда шрифт, указанный в исходном документе, недоступен и заменяется либо правилом, предоставленным клиентом FontSubstitutegroupdocs.conversion.contracts/fontsubstitute, либо настроенным шрифтом по умолчанию, либо внутренним резервным вариантом конвертационного конвейера."
type: docs
weight: 80
url: /ru/net/groupdocs.conversion/conversionevents/onfontsubstituted/
---
## ConversionEvents.OnFontSubstituted property

Срабатывает, когда шрифт, указанный в исходном документе, недоступен и заменяется (либо правилом, предоставленным клиентом [`FontSubstitute`](../../../groupdocs.conversion.contracts/fontsubstitute), либо настроенным шрифтом по умолчанию, либо внутренним резервным вариантом конвертационного конвейера).

```csharp
public Action<FontSubstitutionContext> OnFontSubstituted { get; set; }
```

### Примечания

Событие дедуплицируется по `(SourceFileName, OriginalFontName)` в рамках одного вызова `Converter.Convert(...)` — подписчики получают не более одного уведомления о каждом недостающем шрифте для исходного документа. Срабатывает синхронно в потоке конвертации. Не генерируется для конвертации изображений.

Для презентационных документов замена шрифтов обнаруживается только в Windows, поскольку движок определяет её с помощью сопоставления шрифтов, специфичного для платформы, которое недоступно в других операционных системах.

### См. также

* class [FontSubstitutionContext](../../../groupdocs.conversion.contracts/fontsubstitutioncontext)
* class [ConversionEvents](../../conversionevents)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
