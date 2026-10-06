---
title: "image_saving_callback プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "Markdown を保存する際に画像ごとに一度呼び出されるコールバックです。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.convert/markdownoptions/image_saving_callback/
is_root: false
weight: 2020
---


## image_saving_callback property

Markdown を保存する際に画像ごとに一度呼び出されるコールバックです。呼び出し元が画像を外部に保存し、ドキュメントに埋め込まれた URI を置き換えることを可能にします。None でない場合、[`MarkdownOptions.export_images_as_base64`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/export_images_as_base64/) より優先されます。

### Definition:
```python
@property
def image_saving_callback(self):
    ...
@image_saving_callback.setter
def image_saving_callback(self, value):
    ...
```

### 関連項目
* class [`MarkdownOptions`](/conversion/python-net/groupdocs.conversion.options.convert/markdownoptions/)
