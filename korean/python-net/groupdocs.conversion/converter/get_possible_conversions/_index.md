---
title: "get_possible_conversions 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "소스 문서에 대한 가능한 변환을 검색합니다."
type: docs
url: /ko/python-net/groupdocs.conversion/converter/get_possible_conversions/
is_root: false
weight: 1090
---


## get_possible_conversions

소스 문서에 대한 가능한 변환을 검색합니다.

- Learn more about supported conversions: [Full list of supported conversions](https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats)
- Learn more about available conversions: [How to get supported conversions in code](https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions)

```python
def get_possible_conversions(self):
    ...
```

**Returns:** PossibleConversions

### 예제

```python
from groupdocs.conversion import Converter

with Converter("report.xlsx") as converter:
    conversions = converter.get_possible_conversions()
    primary = [c.format for c in conversions.all if c.is_primary]
    print(f"Primary targets for {conversions.source.description}: {primary}")
```

### 또 보기
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
