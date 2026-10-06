---
title: "DocumentInfo 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "다형 문서 정보를 검색하기 위한 기본 구현입니다."
type: docs
url: /ko/python-net/groupdocs.conversion.contracts/documentinfo/
is_root: false
weight: 120
---


## DocumentInfo class

다형 문서 정보를 검색하기 위한 기본 구현입니다.

인스턴스는 `Converter.get_document_info()`에 의해 반환되며 형식, 페이지 수, 생성 날짜, 크기 및 형식별 속성과 같은 메타데이터를 노출합니다.

DocumentInfo 형식은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/get_string/) |  |

### 속성들
| 속성 | 설명 |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/creation_date/) | 문서의 생성 날짜. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/format/) | 문서의 형식. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) | 문서의 총 페이지 수. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/property_names/) | 이 속성은 [`IDocumentInfo.property_names`](/conversion/python-net/groupdocs.conversion.contracts/idocumentinfo/property_names/)를 구현합니다. |
| [size](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/size/) | 문서의 크기(바이트 단위). |

### 예제

```python
from groupdocs.conversion import Converter

def show_document_info(path):
    with Converter(path) as converter:
        info = converter.get_document_info()
        print("Format:", info.format)
        print("Pages count:", info.pages_count)
        print("Creation date:", info.creation_date)
        print("Size (bytes):", info.size)

# 예제 사용법
show_document_info("./lorem-ipsum.txt")
```

### 또 보기
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
