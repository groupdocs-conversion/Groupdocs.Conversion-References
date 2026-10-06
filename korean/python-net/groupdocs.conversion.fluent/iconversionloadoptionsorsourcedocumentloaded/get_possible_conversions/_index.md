---
title: "get_possible_conversions 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "소스 문서에 대한 가능한 변환을 검색합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/get_possible_conversions/
is_root: false
weight: 1080
---


## get_possible_conversions

소스 문서에 대한 가능한 변환을 검색합니다.

반환된 객체는 기본 및 보조 형식을 포함한 모든 변환 옵션에 대한 접근을 제공하며, 소스 파일에 대한 메타데이터를 포함합니다.

```python
def get_possible_conversions(self):
    ...
```

**Returns:** GroupDocs.Conversion.Fluent.PossibleConversions: An object containing the source description and collections of conversion formats.

### 예제

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### 또 보기
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
