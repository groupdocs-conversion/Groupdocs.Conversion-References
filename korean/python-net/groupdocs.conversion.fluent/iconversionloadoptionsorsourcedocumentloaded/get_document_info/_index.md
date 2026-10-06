---
title: "get_document_info 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "페이지 수 및 파일 유형에 특화된 기타 속성을 포함한 소스 문서 정보를 검색합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

페이지 수 및 파일 유형에 특화된 기타 속성을 포함한 소스 문서 정보를 검색합니다.

```python
def get_document_info(self):
    ...
```

**Returns:** DocumentInfo: An object containing details about the source document, such as format, page count, creation date, size, and type‑specific properties.

### 예제

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### 또 보기
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
