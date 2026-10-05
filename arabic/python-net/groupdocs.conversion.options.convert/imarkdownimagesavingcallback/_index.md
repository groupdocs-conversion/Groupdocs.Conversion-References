---
title: "فئة IMarkdownImageSavingCallback"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يتعامل مع معالجة مخصصة للصور أثناء الحفظ إلى Markdown."
type: docs
url: /ar/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/
is_root: false
weight: 150
---


## IMarkdownImageSavingCallback class

يتعامل مع معالجة مخصصة للصور أثناء الحفظ إلى Markdown.

يُستدعى مرة واحدة لكل صورة؛ عدّل [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/) للتحكم في URI المضمن في مخرجات Markdown و/أو لإعادة توجيه مكان كتابة بايتات الصورة.

يعرض نوع IMarkdownImageSavingCallback الأعضاء التالية:

### الطرق
| طريقة | الوصف |
| :- | :- |
| [image_saving](/conversion/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/image_saving/#args) | يُستدعى لكل صورة تُكتب في مستند Markdown. |
| [image_saving_markdown_image_saving_args](/conversion/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/image_saving_markdown_image_saving_args/) |  |

### مثال

```python
import io
import os
from GroupDocs.Conversion import Converter
from GroupDocs.Conversion.Options.Convert import WordProcessingConvertOptions, MarkdownImageSavingArgs
from GroupDocs.Conversion.FileTypes import WordProcessingFileType

# السيناريو 1 — التقاط بايتات الصورة في الذاكرة وتضمين معرفات العنصر النائب
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
# captured["image0"], captured["image1"], ... الآن تحتفظ بايتات الصورة

# السيناريو 2 — حفظ الصور على القرص جنبًا إلى جنب مع ملف .md والإشارة إليها باسم الملف
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
# ./out/image0.png, ./out/image1.png, ... يتم كتابتها وإغلاقها بواسطة المحول.
```

### انظر أيضًا
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
