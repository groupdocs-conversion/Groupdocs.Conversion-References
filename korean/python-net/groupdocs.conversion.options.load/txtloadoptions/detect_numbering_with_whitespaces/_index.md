---
title: "detect_numbering_with_whitespaces 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "이 속성은 일반 텍스트 문서를 변환할 때 번호 매기기 목록 항목을 어떻게 인식할지 지정합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/
is_root: false
weight: 2020
---


## detect_numbering_with_whitespaces property

이 속성은 일반 텍스트 문서를 변환할 때 번호 매기기 목록 항목을 인식하는 방식을 지정합니다. 기본값은 True입니다.

이 옵션이 False로 설정되면, 목록 인식 알고리즘은 목록 번호가 마침표, 오른쪽 괄호 또는 글머리 기호(예: "•", "*", "-", "o") 중 하나로 끝날 때 목록 단락을 감지합니다.

이 옵션이 True로 설정되면, 공백도 목록 번호 구분자로 사용됩니다: 아라비아식 번호 매기기(예: 1., 1.1.2.)에 대한 목록 인식 알고리즘은 공백과 마침표(".") 기호를 모두 사용합니다.

### Definition:
```python
@property
def detect_numbering_with_whitespaces(self):
    ...
@detect_numbering_with_whitespaces.setter
def detect_numbering_with_whitespaces(self, value):
    ...
```

### 또 보기
* class [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/)
