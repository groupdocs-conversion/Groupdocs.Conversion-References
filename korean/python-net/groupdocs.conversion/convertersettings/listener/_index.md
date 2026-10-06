---
title: "listener 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "변환 상태와 진행 상황을 모니터링하기 위해 사용되는 컨버터 리스너 구현으로, Started, Progress, Completed 콜백이 ConversionEvents.onconversionstarted에 전달됩니다…"
type: docs
url: /ko/python-net/groupdocs.conversion/convertersettings/listener/
is_root: false
weight: 2030
---


## listener property

변환 상태와 진행 상황을 모니터링하기 위해 사용되는 컨버터 리스너 구현으로, Started, Progress 및 Completed 콜백이 [`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/), [`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/), 그리고 [`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) 로 전달되며, [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 생성 중에 사용됩니다.

### Definition:
```python
@property
def listener(self):
    ...
@listener.setter
def listener(self, value):
    ...
```

### 또 보기
* class [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/)
