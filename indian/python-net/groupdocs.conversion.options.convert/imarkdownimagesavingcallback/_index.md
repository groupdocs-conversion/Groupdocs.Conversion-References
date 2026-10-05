---
title: "IMarkdownImageSavingCallback क्लास"
second_title: "GroupDocs.Conversion Python के लिए .NET के माध्यम से API संदर्भ"
description: "मार्कडाउन में सहेजते समय छवियों की कस्टम प्रोसेसिंग को संभालता है।"
type: docs
url: /hi/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/
is_root: false
weight: 150
---


## IMarkdownImageSavingCallback class

मार्कडाउन में सहेजते समय छवियों की कस्टम प्रोसेसिंग को संभालता है।

प्रति छवि एक बार बुलाया जाता है; [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/) को संशोधित करके मार्कडाउन आउटपुट में एम्बेड किए गए URI को नियंत्रित करें और/या जहाँ छवि बाइट्स लिखी जाती हैं उसे पुनः निर्देशित करें।

IMarkdownImageSavingCallback प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### विधियाँ
| विधि | विवरण |
| :- | :- |
| [image_saving](/conversion/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/image_saving/#args) | मार्कडाउन दस्तावेज़ में लिखी जा रही प्रत्येक छवि के लिए बुलाया जाता है। |
| [image_saving_markdown_image_saving_args](/conversion/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/image_saving_markdown_image_saving_args/) |  |

### उदाहरण

```python
import io
import os
from GroupDocs.Conversion import Converter
from GroupDocs.Conversion.Options.Convert import WordProcessingConvertOptions, MarkdownImageSavingArgs
from GroupDocs.Conversion.FileTypes import WordProcessingFileType

# परिदृश्य 1 — मेमोरी में छवि बाइट्स को कैप्चर करें और प्लेसहोल्डर आईडी एम्बेड करें
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
# captured[\"image0\"], captured[\"image1\"], ... अब छवि बाइट्स रखती हैं

# परिदृश्य 2 — .md के साथ डिस्क पर छवियों को स्थायी रूप से सहेजें और उन्हें फ़ाइल नाम द्वारा संदर्भित करें
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
# ./out/image0.png, ./out/image1.png, ... को कनवर्टर द्वारा लिखा और बंद किया जाता है।
```

### साथ ही देखें
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
