---
title: "FontNameSubstitutionEnabled"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Автоматически заменяет отсутствующие шрифты на основе имени шрифта. По умолчанию false."
type: docs
weight: 140
url: /ru/net/groupdocs.conversion.options.load/wordprocessingloadoptions/fontnamesubstitutionenabled/
---
## WordProcessingLoadOptions.FontNameSubstitutionEnabled property

Автоматически заменяет отсутствующие шрифты на основе имени шрифта. По умолчанию: false.

```csharp
public bool FontNameSubstitutionEnabled { get; set; }
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
