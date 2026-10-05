---
title: "__init__ 构造函数"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "使用指定的水印文本初始化一个 WatermarkTextOptions 实例。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.convert/watermarktextoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#text}

使用指定的水印文本初始化一个 WatermarkTextOptions 实例。

```python
def __init__(self, text):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | `str` | 用作水印的文本。 |

### 示例

```python
from groupdocs.conversion.options.convert import WatermarkTextOptions

# 创建一个文本为 "DRAFT" 的水印
watermark = WatermarkTextOptions("DRAFT")
```

### 另见
* class [`WatermarkTextOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/)
