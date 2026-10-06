---
title: "schema_location 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "schemalocation은 URI 쌍의 공백으로 구분된 목록이며, 각 쌍의 첫 번째 URI는 네임스페이스 URI이고 두 번째 URI는 해당 네임스페이스의 XML 스키마 경로입니다."
type: docs
url: /ko/python-net/groupdocs.conversion.options.load/gmlloadoptions/schema_location/
is_root: false
weight: 2040
---


## schema_location property

schema_location은 URI 쌍의 공백으로 구분된 목록이며, 각 쌍의 첫 번째 URI는 네임스페이스 URI이고 두 번째 URI는 해당 네임스페이스의 XML 스키마 경로입니다.

None으로 설정하면, Conversion은 문서의 루트 요소에서 schemaLocation 속성을 읽으려고 시도합니다. 기본값은 None입니다.

### Definition:
```python
@property
def schema_location(self):
    ...
@schema_location.setter
def schema_location(self, value):
    ...
```

### 또 보기
* class [`GmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/)
