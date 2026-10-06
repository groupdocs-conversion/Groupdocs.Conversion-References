---
title: "on_conversion_by_page_failed 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "페이지별 변환이 실패했을 때 호출되는 이벤트 핸들러입니다."
type: docs
url: /ko/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/
is_root: false
weight: 2060
---


## on_conversion_by_page_failed property

페이지별 변환이 실패했을 때 호출되는 이벤트 핸들러입니다.

하위 호환성을 위해 존중됩니다: 해당 값은 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 생성 시 내부 이벤트 백에 병합되며 ([`ConversionEvents.on_page_failed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/)에 매핑됩니다) 동일한 핸들러가 `events` 생성자 매개변수에 설정된 경우에는 재정의됩니다.

### Definition:
```python
@property
def on_conversion_by_page_failed(self):
    ...
@on_conversion_by_page_failed.setter
def on_conversion_by_page_failed(self, value):
    ...
```

### 또 보기
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
