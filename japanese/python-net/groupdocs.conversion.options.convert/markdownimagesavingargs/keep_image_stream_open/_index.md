---
title: "keep_image_stream_open プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "このプロパティは、変換後にコンバータが画像ストリームを開いたままにするかどうかを決定します。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/keep_image_stream_open/
is_root: false
weight: 2030
---


## keep_image_stream_open property

このプロパティは、変換後にコンバータが画像ストリームを開いたままにするかどうかを決定します。

False（デフォルト）の場合、コンバータは書き込み後に [`MarkdownImageSavingArgs.image_stream`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/image_stream/) を閉じます — これはディスクへフラッシュすべき `io.RawIOBase` の置換に慣用的です。True に設定すると、変換完了後もストリームを開いたままにします（自分で読み取ることを想定した `io.BytesIO` に典型的です）。この場合、呼び出し側が破棄を管理します。

### Definition:
```python
@property
def keep_image_stream_open(self):
    ...
@keep_image_stream_open.setter
def keep_image_stream_open(self, value):
    ...
```

### 関連項目
* class [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/)
