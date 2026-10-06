---
title: "IMarkdownImageSavingCallback-klass"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Hantera anpassad bildbehandling vid sparande till Markdown."
type: docs
url: /sv/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/
is_root: false
weight: 150
---


## IMarkdownImageSavingCallback class

Hantera anpassad bildbehandling vid sparande till Markdown.

Anropas en gång per bild; modifiera [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/) för att kontrollera URI:n som bäddas in i Markdown-utdata och/eller omdirigera var bildbytarna skrivs.

Typen IMarkdownImageSavingCallback visar följande medlemmar:

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [image_saving](/conversion/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/image_saving/#args) | Anropas för varje bild som skrivs till Markdown-dokumentet. |
| [image_saving_markdown_image_saving_args](/conversion/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/image_saving_markdown_image_saving_args/) |  |

### Exempel

```python
import io
import os
from GroupDocs.Conversion import Converter
from GroupDocs.Conversion.Options.Convert import WordProcessingConvertOptions, MarkdownImageSavingArgs
from GroupDocs.Conversion.FileTypes import WordProcessingFileType

# Scenario 1 — fånga bildbytarna i minnet och bädda in platshållar-id:n
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
# captured["image0"], captured["image1"], ... innehåller nu bildbytarna

# Scenario 2 — spara bilder på disk tillsammans med .md-filen och referera till dem med filnamn
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
# ./out/image0.png, ./out/image1.png, ... skrivs och stängs av konverteraren.
```

### Se även
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
