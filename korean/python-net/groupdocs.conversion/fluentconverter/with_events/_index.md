---
title: "with_events 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "변환 라이프사이클 이벤트 핸들러와 함께 진입 단계에서 유창 체인을 시작합니다."
type: docs
url: /ko/python-net/groupdocs.conversion/fluentconverter/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

변환 라이프사이클 이벤트 핸들러와 함께 진입 단계에서 유창 체인을 시작합니다.

```python
def with_events(cls, configure):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | `ConversionEvents` 백을 변형하는 호출 가능 객체. |

**Returns:** The source-selection stage, allowing `Load` to be chained.

### 또 보기
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
