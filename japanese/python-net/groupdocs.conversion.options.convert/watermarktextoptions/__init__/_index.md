---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "指定された透かしテキストで WatermarkTextOptions インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.convert/watermarktextoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#text}

指定された透かしテキストで WatermarkTextOptions インスタンスを初期化します。

```python
def __init__(self, text):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| text | `str` | 透かしとして使用されるテキストです。 |

### 例

```python
from groupdocs.conversion.options.convert import WatermarkTextOptions

# テキスト "DRAFT" を使用して透かしを作成します。
watermark = WatermarkTextOptions("DRAFT")
```

### 関連項目
* class [`WatermarkTextOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/)
