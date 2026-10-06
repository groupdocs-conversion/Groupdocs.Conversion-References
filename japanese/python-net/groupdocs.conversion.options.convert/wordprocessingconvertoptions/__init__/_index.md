---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "WordProcessingConvertOptions の新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

新しいインスタンスを初期化します [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/).

```python
def __init__(self):
    ...
```

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

with Converter("./business-plan.docx") as converter:
    options = WordProcessingConvertOptions()
    options.format = WordProcessingFileType.TXT
    converter.convert("./business-plan.txt", options)
```

### 関連項目
* class [`WordProcessingConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/)
