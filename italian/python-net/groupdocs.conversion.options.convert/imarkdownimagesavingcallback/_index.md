---
title: "classe IMarkdownImageSavingCallback"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Gestisce l'elaborazione personalizzata delle immagini durante il salvataggio in Markdown."
type: docs
url: /it/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/
is_root: false
weight: 150
---


## IMarkdownImageSavingCallback class

Gestisce l'elaborazione personalizzata delle immagini durante il salvataggio in Markdown.

Invocato una volta per immagine; modifica [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/) per controllare l'URI incorporato nell'output Markdown e/o reindirizzare dove vengono scritti i byte dell'immagine.

Il tipo IMarkdownImageSavingCallback espone i seguenti membri:

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [image_saving](/conversion/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/image_saving/#args) | Chiamato per ogni immagine scritta nel documento Markdown. |
| [image_saving_markdown_image_saving_args](/conversion/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/image_saving_markdown_image_saving_args/) |  |

### Esempio

```python
import io
import os
from GroupDocs.Conversion import Converter
from GroupDocs.Conversion.Options.Convert import WordProcessingConvertOptions, MarkdownImageSavingArgs
from GroupDocs.Conversion.FileTypes import WordProcessingFileType

# Scenario 1 — cattura i byte dell'immagine in memoria e incorpora gli ID segnaposto
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
# captured[\"image0\"], captured[\"image1\"], ... ora contengono i byte dell'immagine

# Scenario 2 — persisti le immagini su disco accanto al file .md e riferiscile per nome file
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
# ./out/image0.png, ./out/image1.png, ... vengono scritti e chiusi dal convertitore.
```

### Vedi anche
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
