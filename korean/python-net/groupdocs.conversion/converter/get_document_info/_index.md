---
title: "get_document_info 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "페이지 수 및 파일 유형에 특화된 기타 속성을 포함한 소스 문서 정보를 검색합니다."
type: docs
url: /ko/python-net/groupdocs.conversion/converter/get_document_info/
is_root: false
weight: 1080
---


## get_document_info

페이지 수 및 파일 유형에 특화된 기타 속성을 포함한 소스 문서 정보를 검색합니다.

변환된 문서에 대해 자세히 알아보세요 – 파일 유형, 페이지 수, 생성 날짜 및 기타 많은 형식별 속성:
- How to get document info (https://docs.groupdocs.com/display/conversionnet/Get+document+info)

```python
def get_document_info(self):
    ...
```

**Returns:** Document information as `IDocumentInfo`.

### 예제

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### 또 보기
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
