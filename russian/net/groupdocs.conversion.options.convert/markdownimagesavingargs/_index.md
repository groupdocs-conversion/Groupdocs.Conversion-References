---
title: "MarkdownImageSavingArgs"
second_title: "GroupDocs.Conversion для .NET API Reference"
description: "Аргументы, передаваемые в ImageSaving./imarkdownimagesavingcallback/imagesaving."
type: docs
weight: 2000
url: /ru/net/groupdocs.conversion.options.convert/markdownimagesavingargs/
---
## MarkdownImageSavingArgs class

Аргументы, передаваемые в [`ImageSaving`](../imarkdownimagesavingcallback/imagesaving).

```csharp
public sealed class MarkdownImageSavingArgs
```

## Свойства

| Имя | Описание |
| --- | --- |
| [ImageFileName](../../groupdocs.conversion.options.convert/markdownimagesavingargs/imagefilename) { get; set; } | Имя файла (или идентификатор заполнителя), встроенное как URI изображения в выводе Markdown. Присвойте значение, чтобы изменить URI. |
| [ImageStream](../../groupdocs.conversion.options.convert/markdownimagesavingargs/imagestream) { get; set; } | Поток назначения, в который конвертер запишет байты изображения после возврата этого обратного вызова. Замените его своим записываемым потоком (например, FileStream для сохранения на диск или MemoryStream, который вы планируете читать позже). |
| [KeepImageStreamOpen](../../groupdocs.conversion.options.convert/markdownimagesavingargs/keepimagestreamopen) { get; set; } | Когда false (по умолчанию), конвертер закрывает [`ImageStream`](./imagestream) после записи — типично для замен FileStream, которые должны быть сброшены на диск. Установите true, чтобы оставить поток открытым после завершения конвертации (обычно для MemoryStream, который вы планируете читать самостоятельно); тогда вызывающий код отвечает за освобождение. |

### См. также

* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.conversion.dll -->
