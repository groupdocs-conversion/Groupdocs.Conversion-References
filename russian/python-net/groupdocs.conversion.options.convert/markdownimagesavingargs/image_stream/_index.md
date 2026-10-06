---
title: "свойство image_stream"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Поток назначения, в который конвертер запишет байты изображения после возврата из этого обратного вызова."
type: docs
url: /ru/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/
is_root: false
weight: 2020
---


## image_stream property

Поток назначения, в который конвертер запишет байты изображения после возврата из этого обратного вызова.

Замените его собственным записываемым потоком (например, `io.RawIOBase` для сохранения на диск или `io.BytesIO`, который вы планируете читать позже).

### Definition:
```python
@property
def image_stream(self):
    ...
@image_stream.setter
def image_stream(self, value):
    ...
```

### См. также
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
