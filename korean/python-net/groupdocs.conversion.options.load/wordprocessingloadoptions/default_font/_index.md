---
title: "default_font 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "WordProcessing 문서의 기본 글꼴."
type: docs
url: /ko/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/default_font/
is_root: false
weight: 2080
---


## default_font property

WordProcessing 문서의 기본 글꼴.

참고: 대체 순서는 다음과 같습니다:
- Automatically substitute missing fonts based on font name (if enabled).
- Automatically substitute missing fonts based on FontConfig (if enabled).
- Substitute missing fonts based on FontSubstitutes (if set).
- Automatically substitute missing fonts based on FontInfo (if enabled).
- Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def default_font(self):
    ...
@default_font.setter
def default_font(self, value):
    ...
```

### 또 보기
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
