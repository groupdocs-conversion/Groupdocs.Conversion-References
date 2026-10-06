---
title: "with_options 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "변환 옵션을 설정합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/with_options/
is_root: false
weight: 1060
---


## with_options {#convert_options}

변환 옵션을 설정합니다.

```python
def with_options(self, convert_options):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| convert_options | `ConvertOptions` | 변환 옵션 |

**Returns:** Interface to continue conversion building.

## with_options {#convert_options_provider}

변환 옵션을 설정합니다.

```python
def with_options(self, convert_options_provider):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | 변환 옵션. `ConvertContext`가 제공자에게 전달됩니다. |

**Returns:** Interface to continue conversion building.

### 또 보기
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
