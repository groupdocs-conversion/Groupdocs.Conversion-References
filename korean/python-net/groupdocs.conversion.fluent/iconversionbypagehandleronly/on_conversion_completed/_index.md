---
title: "on_conversion_completed 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "페이지 변환이 성공적으로 완료될 때 호출되는 콜백을 등록합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#on_completed}

페이지 변환이 성공적으로 완료될 때 호출되는 콜백을 등록합니다.

```python
def on_conversion_completed(self, on_completed):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| on_completed | `Action[ConvertedPageContext]` | 완료를 처리하는 호출 가능 객체로, 변환된 페이지 컨텍스트를 받습니다. |

**Returns:** Interface to continue conversion building, allowing only OnConversionFailed or Convert/Compress.

### 또 보기
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
