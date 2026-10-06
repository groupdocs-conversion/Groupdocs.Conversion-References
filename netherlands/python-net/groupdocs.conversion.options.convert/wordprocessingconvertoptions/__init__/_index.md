---
title: "__init__-constructor"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van WordProcessingConvertOptions."
type: docs
url: /nl/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/).

```python
def __init__(self):
    ...
```

### Voorbeeld

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

with Converter("./business-plan.docx") as converter:
    options = WordProcessingConvertOptions()
    options.format = WordProcessingFileType.TXT
    converter.convert("./business-plan.txt", options)
```

### Zie ook
* class [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/)
