---
title: "on_conversion_failed 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "페이지 변환이 실패할 때 호출되는 콜백을 등록합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_failed/
is_root: false
weight: 1060
---


## on_conversion_failed {#on_failed}

페이지 변환이 실패할 때 호출되는 콜백을 등록합니다.

```python
def on_conversion_failed(self, on_failed):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| on_failed | `Action[ConvertedPageContext, Exception]` | 실패를 처리하는 호출 가능 객체로, 변환된 페이지 컨텍스트와 실패를 일으킨 예외를 받습니다. |

**Returns:** Interface to continue conversion building, allowing only `OnConversionCompleted` or `Convert`/`Compress`.

### 또 보기
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
