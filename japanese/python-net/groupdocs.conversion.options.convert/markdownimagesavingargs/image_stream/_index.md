---
title: "image_stream プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "このコールバックが戻った後、コンバータが画像バイトを書き込む宛先ストリーム。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/
is_root: false
weight: 2020
---


## image_stream property

このコールバックが戻った後、コンバータが画像バイトを書き込む宛先ストリーム。

独自の書き込み可能ストリームに置き換えてください（例: ディスク永続化用の `io.RawIOBase` や、後で読み取ることを想定した `io.BytesIO`）。

### Definition:
```python
@property
def image_stream(self):
    ...
@image_stream.setter
def image_stream(self, value):
    ...
```

### 関連項目
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
