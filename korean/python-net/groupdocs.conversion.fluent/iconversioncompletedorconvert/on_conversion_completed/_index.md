---
title: "on_conversion_completed 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "변환된 문서 스트림을 받습니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/on_conversion_completed/
is_root: false
weight: 1040
---


## on_conversion_completed {#converted_file_stream}

변환된 문서 스트림을 수신합니다. `ConvertTo(string fileName)` 또는 `ConvertTo(convertedStreamProvider)`가 설정된 경우에만 발생합니다.

```python
def on_conversion_completed(self, converted_file_stream):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| converted_file_stream | `Action[ConvertedContext]` | 변환된 문서 스트림 제공자 (`ConvertedContext`). |

**Returns:** Interface to continue conversion building.

### 또 보기
* class [`IConversionCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversioncompletedorconvert/)
