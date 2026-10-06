---
title: "set 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "캐시 항목을 캐시에 삽입합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.caching/filecache/set/
is_root: false
weight: 1040
---


## set {#key-value}

캐시 항목을 캐시에 삽입합니다.

```python
def set(self, key, value):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| key | `str` | 캐시 항목에 대한 고유 식별자입니다. |
| value | `Any` | 삽입할 객체입니다. |

### 예제

```python
from groupdocs.conversion import ConverterSettings, FileCache

# 파일 기반 캐시를 사용하여 변환기 설정 만들기
settings = ConverterSettings()
settings.cache = FileCache()

# 캐시 안에 객체를 저장합니다
settings.cache.set("my_document", document)
```

### 또 보기
* class [`FileCache`](/conversion/python-net/groupdocs.conversion.caching/filecache/)
