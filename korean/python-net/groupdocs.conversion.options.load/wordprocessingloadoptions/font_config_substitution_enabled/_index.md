---
title: "font_config_substitution_enabled 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "이 속성은 시스템 FontConfig를 기반으로 누락된 글꼴을 자동으로 대체하도록 합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/font_config_substitution_enabled/
is_root: false
weight: 2110
---


## font_config_substitution_enabled property

이 속성은 시스템 FontConfig을 기반으로 누락된 글꼴을 자동으로 대체하도록 합니다. 기본값은 False입니다.

참고: 대체 순서는 다음과 같습니다:
- Automatically substitute missing fonts based on font name (if enabled).
- Automatically substitute missing fonts based on FontConfig (if enabled).
- Substitute missing fonts based on FontSubstitutes (if set).
- Automatically substitute missing fonts based on FontInfo (if enabled).
- Substitute missing fonts based on DefaultFont (if set).

### Definition:
```python
@property
def font_config_substitution_enabled(self):
    ...
@font_config_substitution_enabled.setter
def font_config_substitution_enabled(self, value):
    ...
```

### 또 보기
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
