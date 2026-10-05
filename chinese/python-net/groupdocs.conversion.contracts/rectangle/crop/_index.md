---
title: "crop 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "通过移除指定的边距创建当前矩形的裁剪版本。"
type: docs
url: /zh/python-net/groupdocs.conversion.contracts/rectangle/crop/
is_root: false
weight: 1010
---


## crop {#crop_left-crop_top-crop_right-crop_bottom}

通过移除指定的边距创建当前矩形的裁剪版本。

```python
def crop(self, crop_left, crop_top, crop_right, crop_bottom):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| crop_left | `int` | 从左侧移除的像素数量。 |
| crop_top | `int` | 从顶部移除的像素数量。 |
| crop_right | `int` | 从右侧移除的像素数量。 |
| crop_bottom | `int` | 从底部移除的像素数量。 |

**Returns:** Rectangle: A new cropped rectangle.

### 另见
* class [`Rectangle`](/conversion/python-net/groupdocs.conversion.contracts/rectangle/)
