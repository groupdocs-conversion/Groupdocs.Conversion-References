---
title: "on_font_substituted 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "소스 문서에서 참조된 글꼴이 사용 가능하지 않을 때 발생하는 이벤트이며, (고객이 제공한 FontSubstitute 규칙, 구성된 기본 글꼴, 또는 …에 의해 대체됩니다."
type: docs
url: /ko/python-net/groupdocs.conversion/conversionevents/on_font_substituted/
is_root: false
weight: 2070
---


## on_font_substituted property

소스 문서에서 참조된 글꼴을 사용할 수 없고 대체될 때 발생하는 이벤트이며(고객 제공 [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) 규칙, 구성된 기본 글꼴, 또는 변환 파이프라인의 내부 대체에 의해).

이 이벤트는 단일 `Converter.Convert(...)` 호출 내에서 `(SourceFileName, OriginalFontName)`별로 중복 제거됩니다 — 구독자는 소스 문서당 누락된 글꼴당 최대 하나의 알림만 받습니다. 변환 스레드에서 동기적으로 발생합니다. 이미지 변환에 대해서는 발생하지 않습니다.

프레젠테이션 문서의 경우, 글꼴 대체는 Windows에서만 감지됩니다. 이는 엔진이 다른 운영 체제에서는 사용할 수 없는 플랫폼별 글꼴 매칭을 통해 해결하기 때문입니다.

### Definition:
```python
@property
def on_font_substituted(self):
    ...
@on_font_substituted.setter
def on_font_substituted(self, value):
    ...
```

### 또 보기
* class [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/)
