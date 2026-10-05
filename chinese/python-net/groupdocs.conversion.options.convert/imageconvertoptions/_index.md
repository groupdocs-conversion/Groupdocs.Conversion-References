---
title: "ImageConvertOptions 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "表示将文档转换为图像文件类型的选项。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.convert/imageconvertoptions/
is_root: false
weight: 230
---


## ImageConvertOptions class

表示将文档转换为图像文件类型的选项。

ImageConvertOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/) | 初始化一个新的 ImageConvertOptions 实例。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [background_color](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/background_color/) | 在源格式支持的情况下使用的背景颜色。 |
| [brightness](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/brightness/) | 图像亮度调整。 |
| [cap_resolution_to_page_content](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) | 该属性将每页 PDF 的渲染分辨率限制为页面的原生光栅分辨率，防止渲染分辨率高于嵌入图像的 DPI，并在最终输出中以其原生（更小）的像素尺寸和 DPI 输出页面。 |
| [contrast](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/contrast/) | 对图像应用的对比度调整。 |
| [crop_area](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/crop_area/) | 转换后光栅图像的裁剪区域。 |
| [flip_mode](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/flip_mode/) | 图像翻转模式。 |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/format/) | 输入文档应转换为的目标文件类型。 |
| [gamma](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/gamma/) | 图像伽马调整。 |
| [grayscale](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/grayscale/) | 指示是否将图像转换为灰度的选项。 |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) | 转换后所需的图像高度。 |
| [horizontal_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/horizontal_resolution/) | 转换后所需的图像水平分辨率；默认使用输入文件的分辨率或 96 dpi。 |
| [jpeg_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/jpeg_options/) | JPEG 特定的转换选项。 |
| [min_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/min_resolution/) | 在启用 [`ImageConvertOptions.CapResolutionToPageContent`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) 时，应用于受限渲染 DPI 的每轴下限。 |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/page_number/) | 开始转换的页码。 |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages/) | 要转换的页索引列表。应指定以转换特定页面。 |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages_count/) | 从 `PageNumber` 开始要转换的页数。 |
| [psd_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/psd_options/) | PSD 特定的转换选项。 |
| [rotate_angle](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/rotate_angle/) | 图像旋转角度。 |
| [tiff_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/tiff_options/) | Tiff 特定的转换选项。 |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/use_pdf/) | UsePdf 属性。 |
| [vertical_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/vertical_resolution/) | 转换后所需的图像垂直分辨率。默认分辨率为输入文件的分辨率或 96 dpi。 |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/watermark/) | 水印特定选项。 |
| [webp_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/webp_options/) | WebP 特定的转换选项。 |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) | 转换后所需的图像宽度。 |

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

with Converter("slides.pptx") as converter:
    options = ImageConvertOptions()
    options.format = ImageFileType.PNG
    options.page_number = 1
    options.pages_count = 1
    converter.convert("slide-1.png", options)
```

### Guides
使用 `ImageConvertOptions` 的任务指南：

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)

### 另见
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
