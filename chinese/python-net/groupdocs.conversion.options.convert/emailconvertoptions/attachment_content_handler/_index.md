---
title: "attachment_content_handler 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "用于处理电子邮件附件自定义处理的委托。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.convert/emailconvertoptions/attachment_content_handler/
is_root: false
weight: 2010
---


## attachment_content_handler property

用于处理电子邮件附件自定义处理的委托。

委托接收附件名称 (`str`)、内容类型 (`str`) 和原始附件流 (`io.RawIOBase`)，并必须返回修改后的附件流 (`io.RawIOBase`)。

### Definition:
```python
@property
def attachment_content_handler(self):
    ...
@attachment_content_handler.setter
def attachment_content_handler(self, value):
    ...
```

### 另见
* class [`EmailConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/emailconvertoptions/)
