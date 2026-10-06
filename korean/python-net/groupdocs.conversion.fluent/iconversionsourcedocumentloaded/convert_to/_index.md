---
title: "convert_to 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "변환된 문서를 파일로 저장합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/convert_to/
is_root: false
weight: 1030
---


## convert_to {#file_name}

변환된 문서를 파일로 저장합니다.

```python
def convert_to(self, file_name):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_name | `str` | 변환된 문서. |

**Returns:** Options or handler setup interface to continue conversion building.

## convert_to {#converted_stream_provider}

변환된 문서를 스트림으로 저장합니다.

```python
def convert_to(self, converted_stream_provider):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| converted_stream_provider | `Func[SaveContext, io.RawIOBase]` | 변환된 문서 스트림 공급자 converted_stream_provider arg1arg1: 저장 컨텍스트 |

**Returns:** Options or handler setup interface to continue conversion building

### 또 보기
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
