---
title: "FontTransformations"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Преобразовать существующие шрифты после завершения загрузки документа и замены шрифтов. Трансформации шрифтов могут изменять любые шрифты в документе, включая шрифты, которые были успешно загружены."
type: docs
weight: 160
url: /ru/net/groupdocs.conversion.options.load/wordprocessingloadoptions/fonttransformations/
---
## WordProcessingLoadOptions.FontTransformations property

Трансформирует существующие шрифты после загрузки документа и завершения замены шрифтов. Трансформации шрифтов могут изменять любые шрифты в документе, включая успешно загруженные шрифты.

```csharp
public IList<FontTransformation> FontTransformations { get; set; }
```

### Примечания

**Note:** Font transformations are applied after all font substitution steps are complete.

Трансформации обрабатываются в порядке их появления в списке.

Сценарии использования: изменения стилей, требования к брендингу, улучшения доступности.

### См. также

* class [FontTransformation](../../../groupdocs.conversion.contracts/fonttransformation)
* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
