---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Menginisialisasi instance baru dari WordProcessingConvertOptions."
type: docs
url: /id/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi sebuah instance baru dari [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/).

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

with Converter("./business-plan.docx") as converter:
    options = WordProcessingConvertOptions()
    options.format = WordProcessingFileType.TXT
    converter.convert("./business-plan.txt", options)
```

### Lihat Juga
* class [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/)
