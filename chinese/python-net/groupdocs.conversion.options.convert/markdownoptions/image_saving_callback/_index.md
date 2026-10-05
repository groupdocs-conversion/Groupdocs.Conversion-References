---
title: "image_saving_callback 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "在保存 Markdown 时为每个图像调用的回调。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.convert/markdownoptions/image_saving_callback/
is_root: false
weight: 2020
---


## image_saving_callback property

在保存 Markdown 时，每个图像调用一次的回调。允许调用者在外部持久化图像并替换文档中嵌入的 URI。当不为 None 时，此回调优先于 [`MarkdownOptions.export_images_as_base64`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/export_images_as_base64/)。

### Definition:
```python
@property
def image_saving_callback(self):
    ...
@image_saving_callback.setter
def image_saving_callback(self, value):
    ...
```

### 另见
* class [`MarkdownOptions`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/)
