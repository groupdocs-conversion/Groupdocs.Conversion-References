---
title: "get_all_possible_conversions 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "지원되는 모든 변환을 가져옵니다."
type: docs
url: /ko/python-net/groupdocs.conversion/converter/get_all_possible_conversions/
is_root: false
weight: 1070
---


## get_all_possible_conversions

지원되는 모든 변환을 가져옵니다.

지원되는 변환에 대해 자세히 알아보세요:
- [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_all_possible_conversions(cls):
    ...
```

**Returns:** Collection of all possible conversions.

### 예제

```python
from groupdocs.conversion import Converter

# 가능한 모든 변환을 검색합니다
all_conversions = list(Converter.get_all_possible_conversions())
print(f"Total supported source formats: {len(all_conversions)}")
```

### 또 보기
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
