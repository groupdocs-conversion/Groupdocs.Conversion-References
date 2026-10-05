---
title: "IMarkdownImageSavingCallback 类"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "在保存为 Markdown 时处理图像的自定义过程。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/
is_root: false
weight: 150
---


## IMarkdownImageSavingCallback class

在保存为 Markdown 时处理图像的自定义过程。

对每个图像调用一次；修改 [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/) 以控制嵌入在 Markdown 输出中的 URI，或重定向图像字节的写入位置。

IMarkdownImageSavingCallback 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [image_saving](/conversion/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/image_saving/#args) | 在每个写入 Markdown 文档的图像时被调用。 |
| [image_saving_markdown_image_saving_args](/conversion/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/image_saving_markdown_image_saving_args/) |  |

### 示例

```python
import io
import os
from GroupDocs.Conversion import Converter
from GroupDocs.Conversion.Options.Convert import WordProcessingConvertOptions, MarkdownImageSavingArgs
from GroupDocs.Conversion.FileTypes import WordProcessingFileType

# 场景 1 — 在内存中捕获图像字节并嵌入占位符 ID
class CaptureImagesCallback(IMarkdownImageSavingCallback):
    def __init__(self, images: dict):
        self._index = 0
        self._images = images

    def ImageSaving(self, args: MarkdownImageSavingArgs):
        img_id = f"image{self._index}"
        self._index += 1
        buffer = io.BytesIO()
        self._images[img_id] = buffer
        args.ImageStream = buffer               # redirect image bytes into our buffer
        args.ImageFileName = img_id             # placeholder URI written into the .md
        args.KeepImageStreamOpen = True        # keep buffer readable after Convert() returns

captured = {}
options = WordProcessingConvertOptions()
options.Format = WordProcessingFileType.Md
options.MarkdownOptions.ImageSavingCallback = CaptureImagesCallback(captured)

converter = Converter("source.pdf")
converter.Convert("output.md", options)
# captured[\"image0\"], captured[\"image1\"], ... 现在保存图像字节

# 场景 2 — 将图像持久化到磁盘，与 .md 文件一起，并通过文件名引用它们
class FileImagesCallback(IMarkdownImageSavingCallback):
    def __init__(self, output_folder: str):
        self._output_folder = output_folder
        self._index = 0

    def ImageSaving(self, args: MarkdownImageSavingArgs):
        file_name = f"image{self._index}.png"
        self._index += 1
        path = os.path.join(self._output_folder, file_name)
        args.ImageStream = open(path, "wb")    # converter will write image bytes and close the file
        args.ImageFileName = file_name         # written into the .md as ![](image0.png)

options = WordProcessingConvertOptions()
options.Format = WordProcessingFileType.Md
options.MarkdownOptions.ImageSavingCallback = FileImagesCallback("./out")

converter = Converter("source.pdf")
converter.Convert("./out/output.md", options)
# ./out/image0.png, ./out/image1.png, ... 由转换器写入并关闭。
```

### 另见
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
