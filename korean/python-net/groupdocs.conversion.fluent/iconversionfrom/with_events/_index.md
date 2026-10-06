---
title: "with_events 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "컨버터의 수명 동안 존재하고 각 변환 실행 시 트리거되는 ConversionEvents 백에 변환 라이프사이클 이벤트 핸들러를 등록합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionfrom/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

변환기의 수명 동안 존재하고 각 변환 실행 시 발생하는 [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) 백에 변환 라이프사이클 이벤트 핸들러를 등록합니다.

[`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/) 이전이나 이후에 호출될 수 있습니다.
여러 호출이 누적됩니다: 동일한 내부 백이 각 `configure` 액션에 전달되므로, 이전 호출에서 설정된 핸들러는 나중에 덮어쓰지 않는 한 유지됩니다.

```python
def with_events(self, configure):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | 이벤트 백을 변형하는 액션. |

**Returns:** This stage so that further entry-stage calls or `Load` may be chained.

### 또 보기
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
