---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "새 PdfConvertOptions 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/
is_root: false
weight: 10
---


## __init__

새로운 [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### 또 보기
* class [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/)
