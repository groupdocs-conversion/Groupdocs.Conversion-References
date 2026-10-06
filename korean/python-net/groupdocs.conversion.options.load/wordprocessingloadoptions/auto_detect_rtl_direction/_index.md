---
title: "auto_detect_rtl_direction 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "autodetectrtldirection 속성은 주로 오른쪽에서 왼쪽으로 쓰여진 텍스트가 포함된 단락 및 실행에 대해 변환 전에 bidi 플래그를 복구할지 여부를 결정합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/
is_root: false
weight: 2010
---


## auto_detect_rtl_direction property

auto_detect_rtl_direction 속성은 주로 오른쪽에서 왼쪽으로 쓰여진 텍스트를 가진 단락 및 실행의 bidi 플래그가 변환 전에 복구되는지를 결정합니다.

True(기본값)로 설정하면, 이 속성은 Microsoft Word와 LibreOffice에서 사용되는 휴리스틱을 적용하여, `<w:bidi/>` 없이 OOXML을 내보내고 RTL 스크립트만 포함된 실행에 `<w:rtl w:val=\"0\"/>`가 있는 Google Docs와 같은 도구가 생성한 아랍어/히브리어 문서의 렌더링을 수정합니다. False로 설정하면 소스 마크업의 엄격한 OOXML 해석을 유지합니다.

### Definition:
```python
@property
def auto_detect_rtl_direction(self):
    ...
@auto_detect_rtl_direction.setter
def auto_detect_rtl_direction(self, value):
    ...
```

### 또 보기
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
