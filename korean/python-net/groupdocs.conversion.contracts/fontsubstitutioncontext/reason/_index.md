---
title: "reason 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "변환 파이프라인에서 보고된 그대로의 치환 메시지이며, 그대로이며 구문 분석되지 않았습니다."
type: docs
url: /ko/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/
is_root: false
weight: 2020
---


## reason property

변환 파이프라인에서 보고된 그대로의 치환 메시지이며, 그대로이며 구문 분석되지 않았습니다.

구조적으로 글꼴 이름을 노출하는 문서의 경우 이 값은 None일 수 있습니다 ([`FontSubstitutionContext.original_font_name`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) / [`FontSubstitutionContext.substitute_font_name`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/) 사용); 다른 경우에는 전체 사람이 읽을 수 있는 설명을 포함하며, 여기에는 누락된 글꼴과 대체 글꼴의 이름이 모두 포함됩니다.

### Definition:
```python
@property
def reason(self):
    ...
```

### 또 보기
* class [`FontSubstitutionContext`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/)
