---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "새 ImageConvertOptions 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

새 ImageConvertOptions 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

with Converter("slides.pptx") as converter:
    options = ImageConvertOptions()
    options.format = ImageFileType.PNG
    options.page_number = 1
    options.pages_count = 1
    converter.convert("slide-1.png", options)
```

### 또 보기
* class [`ImageConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/)
