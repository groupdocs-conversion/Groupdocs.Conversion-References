---
title: "convert 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "변환 체인을 실행합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/convert/
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

def convert_document():
    # 소스 문서를 엽니다
    with Converter("./business-plan.docx") as converter:
        # PDF 출력에 대한 변환 옵션을 정의합니다
        pdf_options = PdfConvertOptions()
        # 변환을 수행하고 결과를 저장합니다
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document()
```

### 또 보기
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
