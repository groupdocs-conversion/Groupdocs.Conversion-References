---
title: "convert_by_page_to 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "변환된 페이지를 스트림으로 저장합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionto/convert_by_page_to/
is_root: false
weight: 1010
---


## convert_by_page_to {#converted_stream_provider}

변환된 페이지를 스트림으로 저장합니다.

```python
def convert_by_page_to(self, converted_stream_provider):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| converted_stream_provider | `Func[SavePageContext, io.RawIOBase]` | 변환된 문서 페이지 스트림 제공자. converted_stream_provider arg1arg1: 저장 컨텍스트. |

**Returns:** Page options or handler setup interface to continue conversion building.

### 또 보기
* class [`IConversionTo`](/conversion/python-net/groupdocs.conversion.fluent/iconversionto/)
