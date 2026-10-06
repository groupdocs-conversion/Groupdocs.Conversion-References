---
title: "with_options 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "변환 프로세스에 대한 변환 옵션을 설정합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/with_options/
is_root: false
weight: 1010
---


## with_options {#convert_options}

변환 프로세스에 대한 변환 옵션을 설정합니다.

```python
def with_options(self, convert_options):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| convert_options | `ConvertOptions` | 변환 옵션. |

**Returns:** Handler setup interface to continue conversion building.

## with_options {#options_provider}

제공자 함수를 사용하여 변환 옵션을 설정합니다.

```python
def with_options(self, options_provider):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| options_provider | `Func[ConvertContext, ConvertOptions]` | 변환 컨텍스트를 기반으로 변환 옵션을 제공하는 함수. |

**Returns:** Handler setup interface to continue conversion building.

### 또 보기
* class [`IConversionOptionsOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsonly/)
