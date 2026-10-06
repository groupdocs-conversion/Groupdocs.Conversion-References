---
title: "font_substitutes 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "WordProcessing 문서를 변환할 때 사용되는 글꼴 대체 목록."
type: docs
url: /ko/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_substitutes/
is_root: false
weight: 2140
---


## font_substitutes property

WordProcessing 문서를 변환할 때 사용되는 글꼴 대체 목록.

참고: 대체 순서는 다음과 같습니다:

- 1) Automatically substitute missing fonts based on font name (if enabled).
- 2) Automatically substitute missing fonts based on FontConfig (if enabled).
- 3) Substitute missing fonts based on FontSubstitutes (if set).
- 4) Automatically substitute missing fonts based on FontInfo (if enabled).
- 5) Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_substitutes(self):
    ...
@font_substitutes.setter
def font_substitutes(self, value):
    ...
```

### 또 보기
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
