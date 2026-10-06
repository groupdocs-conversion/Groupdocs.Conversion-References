---
title: "on_conversion_completed 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "페이지 변환이 성공적으로 완료될 때 호출되는 콜백을 등록합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

페이지 변환이 성공적으로 완료될 때 호출되는 콜백을 등록합니다.

다시 호출하면 이전에 설정된 핸들러가 교체됩니다.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | 완료를 처리하기 위한 액션으로, 변환된 페이지 컨텍스트를 받습니다. |

**Returns:** This stage, so additional handlers or `Convert` / `Compress` may be chained.

### 또 보기
* class [`IConversionByPageHandlerFailed`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandlerfailed/)
