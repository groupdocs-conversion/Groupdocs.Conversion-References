---
title: "свойство keep_image_stream_open"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Свойство определяет, оставляет ли конвертер поток изображения открытым после конвертации."
type: docs
url: /ru/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/keep_image_stream_open/
is_root: false
weight: 2030
---


## keep_image_stream_open property

Свойство определяет, оставляет ли конвертер поток изображения открытым после конвертации.

Когда False (по умолчанию), конвертер закрывает [`MarkdownImageSavingArgs.image_stream`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/) после записи — типично для замен `io.RawIOBase`, которые должны быть сброшены на диск. Установите True, чтобы оставить поток открытым после завершения конвертации (обычно для `io.BytesIO`, который вы планируете читать сами); тогда вызывающий код отвечает за освобождение.

### Definition:
```python
@property
def keep_image_stream_open(self):
    ...
@keep_image_stream_open.setter
def keep_image_stream_open(self, value):
    ...
```

### См. также
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
