---
title: "convert 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "변환 체인을 실행합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/convert/
is_root: false
weight: 1030
---


## convert

변환 체인을 실행합니다.

```python
def convert(self):
    ...
```

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### 또 보기
* class [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/)
