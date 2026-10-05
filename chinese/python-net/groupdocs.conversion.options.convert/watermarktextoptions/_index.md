---
title: "WatermarkTextOptions 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "设置已转换文档文字水印的选项。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.convert/watermarktextoptions/
is_root: false
weight: 590
---


## WatermarkTextOptions class

设置已转换文档文字水印的选项。

表示水印外观的配置。可以配置以下属性：

- `text`: The text to be used for the watermark.
- `font`: The font name used for the watermark text.
- `color`: The color of the watermark text.
- `top`: The top offset of the watermark.
- `left`: The left offset of the watermark.
- `width`: The width of the watermark.
- `height`: The height of the watermark.
- `background`: Whether the watermark is rendered in the background.

WatermarkTextOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/__init__/#text) | 使用指定的水印文本初始化一个 WatermarkTextOptions 实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/clone/) | 克隆当前实例。（继承自 [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)） |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | 确定两个对象实例是否相等。 (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | 用作默认的哈希函数。 (继承自 [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### 属性
| 属性 | 描述 |
| :- | :- |
| [color](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/color/) | 如果应用文本水印，则为水印字体颜色。 |
| [text](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/text/) | 水印文本。 |
| [watermark_font](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/watermark_font/) | 当应用文本水印时使用的水印字体。 |
| [auto_align](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/auto_align/) | 当设置为 True 时，水印会自动缩放以适应页面大小。（继承自 [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)） |
| [background](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/background/) | 水印被标记为背景；如果为 True，则放置在底部，否则放置在顶部（默认值为 False）。（继承自 [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)） |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/height/) | 水印高度。（继承自 [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)） |
| [left](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/left/) | 水印左侧位置。（继承自 [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)） |
| [rotation_angle](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/rotation_angle/) | 水印旋转角度。（继承自 [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)） |
| [top](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/top/) | 水印顶部位置。（继承自 [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)） |
| [transparency](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/transparency/) | 水印透明度。取值范围为 0 到 1。值为 0 时完全可见，值为 1 时不可见。（继承自 [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)） |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/width/) | 水印宽度。（继承自 [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)） |

### 示例

```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

with Converter("./professional-services.docx") as converter:
    watermark = WatermarkTextOptions("DRAFT")
    watermark.color = Color.from_argb(128, 211, 211, 211)  # lite gray
    watermark.top = 10
    watermark.left = 10
    watermark.width = 300
    watermark.height = 300
    watermark.background = True

    options = PdfConvertOptions()
    options.pages_count = 1
    options.watermark = watermark

    converter.convert("./professional-services.pdf", options)
```

### Guides
使用 `WatermarkTextOptions` 的任务指南：

* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)

### 另见
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
