---
title: "crop メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "指定された余白を除去して現在の矩形の切り抜きバージョンを作成します。"
type: docs
url: /ja/python-net/groupdocs.conversion.contracts/rectangle/crop/
is_root: false
weight: 1010
---


## crop {#crop_left-crop_top-crop_right-crop_bottom}

指定された余白を除去して現在の矩形の切り抜きバージョンを作成します。

```python
def crop(self, crop_left, crop_top, crop_right, crop_bottom):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| crop_left | `int` | 左側から削除するピクセル数。 |
| crop_top | `int` | 上側から削除するピクセル数。 |
| crop_right | `int` | 右側から削除するピクセル数。 |
| crop_bottom | `int` | 下側から削除するピクセル数。 |

**Returns:** Rectangle: A new cropped rectangle.

### 関連項目
* class [`Rectangle`](/conversion/python-net/groupdocs.conversion.contracts/rectangle/)
