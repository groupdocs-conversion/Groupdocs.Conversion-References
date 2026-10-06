---
title: "IMarkdownImageSavingCallback klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Verwerkt aangepaste verwerking van afbeeldingen bij het opslaan naar Markdown."
type: docs
url: /nl/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/
is_root: false
weight: 150
---


## IMarkdownImageSavingCallback class

Verwerkt aangepaste verwerking van afbeeldingen bij het opslaan naar Markdown.

Eenmaal per afbeelding aangeroepen; wijzig [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/) om de URI die in de Markdown-uitvoer is ingebed te beheersen en/of om te bepalen waar de afbeeldingsbytes worden weggeschreven.

Het IMarkdownImageSavingCallback-type geeft de volgende leden weer:

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [image_saving](/conversion/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/image_saving/#args) | Aangeroepen voor elke afbeelding die naar het Markdown‑document wordt geschreven. |
| [image_saving_markdown_image_saving_args](/conversion/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/image_saving_markdown_image_saving_args/) |  |

### Voorbeeld

```python
import io
import os
from GroupDocs.Conversion import Converter
from GroupDocs.Conversion.Options.Convert import WordProcessingConvertOptions, MarkdownImageSavingArgs
from GroupDocs.Conversion.FileTypes import WordProcessingFileType

# Scenario 1 — leg afbeeldingsbytes vast in het geheugen en voeg placeholder‑ids in.
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
# captured["image0"], captured["image1"], ... bevatten nu de afbeeldingsbytes

# Scenario 2 — sla afbeeldingen op schijf op naast het .md‑bestand en verwijs ernaar via bestandsnaam
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
# ./out/image0.png, ./out/image1.png, ... worden geschreven en gesloten door de converter.
```

### Zie ook
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
