---
title: "with_events 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "컨버터의 수명 동안 존재하고 매 변환 실행 시 트리거되는 ConversionEvents 가방에 변환 라이프사이클 이벤트 핸들러를 등록합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

컨버터의 수명 동안 존재하고 모든 변환 실행 시 트리거되는 [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) 백에 변환 라이프사이클 이벤트 핸들러를 등록합니다.

이는 [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/)와 동일한 진입 단계에 위치합니다. 여러 번 호출하면 누적됩니다: 동일한 내부 가방이 각 `configure` 액션에 전달되므로, 이전 호출에서 설정된 핸들러는 나중에 덮어쓰지 않는 한 유지됩니다.

```python
def with_events(self, configure):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | 이벤트 백을 변형하는 액션. |

**Returns:** The source-selection stage so that `Load` may be chained.

### 또 보기
* class [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/)
