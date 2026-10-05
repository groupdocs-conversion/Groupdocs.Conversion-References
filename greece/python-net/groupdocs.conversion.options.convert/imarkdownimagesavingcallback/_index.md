---
title: "IMarkdownImageSavingCallback κλάση"
second_title: "GroupDocs.Conversion για Python μέσω .NET Αναφορές API"
description: "Διαχειρίζεται προσαρμοσμένη επεξεργασία εικόνων κατά την αποθήκευση σε Markdown."
type: docs
url: /el/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/
is_root: false
weight: 150
---


## IMarkdownImageSavingCallback class

Διαχειρίζεται προσαρμοσμένη επεξεργασία εικόνων κατά την αποθήκευση σε Markdown.

Καλείται μία φορά ανά εικόνα· τροποποιήστε το [`MarkdownImageSavingArgs`](/conversion/python-net/groupdocs.conversion.options.convert/markdownimagesavingargs/) για να ελέγξετε το URI που ενσωματώνεται στην έξοδο Markdown και/ή να ανακατευθύνετε πού γράφονται τα bytes της εικόνας.

Ο τύπος IMarkdownImageSavingCallback εκθέτει τα παρακάτω μέλη:

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [image_saving](/conversion/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/image_saving/#args) | Καλείται για κάθε εικόνα που γράφεται στο έγγραφο Markdown. |
| [image_saving_markdown_image_saving_args](/conversion/python-net/groupdocs.conversion.options.convert/imarkdownimagesavingcallback/image_saving_markdown_image_saving_args/) |  |

### Παράδειγμα

```python
import io
import os
from GroupDocs.Conversion import Converter
from GroupDocs.Conversion.Options.Convert import WordProcessingConvertOptions, MarkdownImageSavingArgs
from GroupDocs.Conversion.FileTypes import WordProcessingFileType

# Σενάριο 1 — σύλληψη των bytes της εικόνας στη μνήμη και ενσωμάτωση ταυτοτήτων placeholder
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
# captured["image0"], captured["image1"], ... τώρα περιέχουν τα bytes της εικόνας

# Σενάριο 2 — αποθήκευση των εικόνων στο δίσκο παράλληλα με το .md και αναφορά σε αυτές με το όνομα αρχείου
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
# ./out/image0.png, ./out/image1.png, ... γράφονται και κλείνουν από τον μετατροπέα.
```

### Δείτε επίσης
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
