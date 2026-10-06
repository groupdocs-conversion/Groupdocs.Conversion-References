---
title: "__init__ yapıcı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "WordProcessingConvertOptions sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

Yeni bir [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/) örneği başlatır.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

with Converter("./business-plan.docx") as converter:
    options = WordProcessingConvertOptions()
    options.format = WordProcessingFileType.TXT
    converter.convert("./business-plan.txt", options)
```

### Ayrıca Bakınız
* class [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/)
