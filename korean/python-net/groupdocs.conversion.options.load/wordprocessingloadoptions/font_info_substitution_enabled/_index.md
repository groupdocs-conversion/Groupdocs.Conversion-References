---
title: "font_info_substitution_enabled 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "이 플래그는 문서의 FontInfo를 기반으로 누락된 글꼴을 자동으로 대체하도록 합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_info_substitution_enabled/
is_root: false
weight: 2120
---


## font_info_substitution_enabled property

문서 내 FontInfo를 기반으로 누락된 글꼴을 자동으로 대체하도록 하는 플래그입니다. 기본값: False.

참고: 대체 순서는 다음과 같습니다:
- Automatically substitute missing fonts based on font name (if enabled).
- Automatically substitute missing fonts based on FontConfig (if enabled).
- Substitute missing fonts based on FontSubstitutes (if set).
- Automatically substitute missing fonts based on FontInfo (if enabled).
- Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_info_substitution_enabled(self):
    ...
@font_info_substitution_enabled.setter
def font_info_substitution_enabled(self, value):
    ...
```

### 또 보기
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
