---
title: "DefaultFont"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Устанавливает шрифт по умолчанию для документа WordProcessing."
type: docs
weight: 90
url: /ru/net/groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont/
---
## WordProcessingLoadOptions.DefaultFont property

Устанавливает шрифт по умолчанию для документа WordProcessing.

```csharp
public string DefaultFont { get; set; }
```

### Примечания

**Note:** The order of substitution is as follows:

1) Автоматически заменять отсутствующие шрифты на основе имени шрифта (если включено).

2) Автоматически заменять отсутствующие шрифты на основе FontConfig (если включено).

3) Заменять отсутствующие шрифты на основе FontSubstitutes (если задано).

4) Автоматически заменять отсутствующие шрифты на основе FontInfo (если включено).

5) Заменять отсутствующие шрифты на основе DefaultFont (если задано).

### См. также

* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
