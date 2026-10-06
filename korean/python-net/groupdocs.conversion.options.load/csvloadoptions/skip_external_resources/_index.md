---
title: "skip_external_resources 속성"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "이 속성은 외부 리소스가 로드되는지 여부를 나타냅니다."
type: docs
url: /ko/python-net/groupdocs.conversion.options.load/csvloadoptions/skip_external_resources/
is_root: false
weight: 2170
---


## skip_external_resources property

속성은 외부 리소스가 로드되는지 여부를 나타냅니다. True인 경우, [`IResourceLoadingOptions.whitelisted_resources`](/conversion/python-net/groupdocs.conversion.options.load/iresourceloadingoptions/whitelisted_resources/) 목록에 있는 리소스를 제외한 모든 외부 리소스가 로드되지 않습니다. 기본값: True.

### Definition:
```python
@property
def skip_external_resources(self):
    ...
@skip_external_resources.setter
def skip_external_resources(self, value):
    ...
```

### 또 보기
* class [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/)
