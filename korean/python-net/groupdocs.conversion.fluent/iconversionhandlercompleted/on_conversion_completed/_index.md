---
title: "on_conversion_completed 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "문서 변환이 성공적으로 완료될 때 호출되는 콜백을 등록합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

문서 변환이 성공적으로 완료될 때 호출되는 콜백을 등록합니다.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| on_completed | `Action[ConvertedContext]` | 완료를 처리하는 액션으로, 변환 컨텍스트를 받습니다. |

**Returns:** The flat handlers stage, so additional handlers or `Convert`/`Compress` may be chained.

### 또 보기
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
