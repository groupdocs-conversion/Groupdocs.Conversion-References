---
title: "cap_resolution_to_page_content 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "此属性将每页 PDF 的渲染分辨率限制为页面的原生光栅分辨率，防止渲染出高于嵌入图像的 DPI，并以原生（更小）的分辨率输出页面…"
type: docs
url: /zh/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/
is_root: false
weight: 2030
---


## cap_resolution_to_page_content property

该属性将每页 PDF 的渲染分辨率限制为页面的原生光栅分辨率，防止渲染分辨率高于嵌入图像的 DPI，并在最终输出中以其原生（更小）的像素尺寸和 DPI 输出页面。

仅影响以图像为主（扫描）的页面；包含文本或矢量内容的页面永不被软化，并以请求的 DPI 输出。当显式设置输出 [`ImageConvertOptions.Width`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) 或 [`ImageConvertOptions.Height`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) 时，此限制将被忽略。默认值为 False（不限制；每页均以请求的 DPI 渲染并输出）。

### Definition:
```python
@property
def cap_resolution_to_page_content(self):
    ...
@cap_resolution_to_page_content.setter
def cap_resolution_to_page_content(self, value):
    ...
```

### 另见
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
