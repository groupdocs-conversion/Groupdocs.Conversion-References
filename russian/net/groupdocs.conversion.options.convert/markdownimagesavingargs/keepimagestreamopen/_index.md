---
title: "KeepImageStreamOpen"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Если значение false (по умолчанию), конвертер закрывает ImageStreamgroupdocs.conversion.options.convert/markdownimagesavingargs/imagestream после записи — типично для замен FileStream, которые должны быть сброшены на диск. Установите true, чтобы оставить поток открытым после завершения конвертации, что обычно требуется для MemoryStream, который вы планируете читать сами; тогда вызывающая сторона отвечает за освобождение."
type: docs
weight: 30
url: /ru/net/groupdocs.conversion.options.convert/markdownimagesavingargs/keepimagestreamopen/
---
## MarkdownImageSavingArgs.KeepImageStreamOpen property

Если значение false (по умолчанию), конвертер закрывает [`ImageStream`](../imagestream) после записи — типично для замен FileStream, которые должны быть сброшены на диск. Установите true, чтобы оставить поток открытым после завершения конвертации (обычно для MemoryStream, который вы планируете читать сами); тогда вызывающая сторона отвечает за освобождение.

```csharp
public bool KeepImageStreamOpen { get; set; }
```

### См. также

* class [MarkdownImageSavingArgs](../../markdownimagesavingargs)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
