---
title: "attachment_content_handler プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "メール添付ファイルのカスタム処理を処理するために使用されるデリゲートです。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.convert/emailconvertoptions/attachment_content_handler/
is_root: false
weight: 2010
---


## attachment_content_handler property

メール添付ファイルのカスタム処理を処理するために使用されるデリゲートです。

デリゲートは添付ファイル名（`str`）、コンテンツタイプ（`str`）、元の添付ストリーム（`io.RawIOBase`）を受け取り、修正された添付ストリーム（`io.RawIOBase`）を返す必要があります。

### Definition:
```python
@property
def attachment_content_handler(self):
    ...
@attachment_content_handler.setter
def attachment_content_handler(self, value):
    ...
```

### 関連項目
* class [`EmailConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/emailconvertoptions/)
