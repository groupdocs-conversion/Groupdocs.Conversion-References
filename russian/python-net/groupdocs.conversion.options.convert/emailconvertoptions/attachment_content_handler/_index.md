---
title: "Свойство attachment_content_handler"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Делегат, используемый для обработки пользовательской обработки вложений электронной почты."
type: docs
url: /ru/python-net/groupdocs.conversion.options.convert/emailconvertoptions/attachment_content_handler/
is_root: false
weight: 2010
---


## attachment_content_handler property

Делегат, используемый для обработки пользовательской обработки вложений электронной почты.

Делегат получает имя вложения (`str`), тип содержимого (`str`) и исходный поток вложения (`io.RawIOBase`), и должен вернуть изменённый поток вложения (`io.RawIOBase`).

### Definition:
```python
@property
def attachment_content_handler(self):
    ...
@attachment_content_handler.setter
def attachment_content_handler(self, value):
    ...
```

### См. также
* class [`EmailConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/emailconvertoptions/)
