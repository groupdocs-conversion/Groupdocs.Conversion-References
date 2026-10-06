---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "지정된 워터마크 텍스트로 WatermarkTextOptions 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.options.convert/watermarktextoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#text}

지정된 워터마크 텍스트로 WatermarkTextOptions 인스턴스를 초기화합니다.

```python
def __init__(self, text):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| text | `str` | 워터마크로 사용할 텍스트입니다. |

### 예제

```python
from groupdocs.conversion.options.convert import WatermarkTextOptions

# 텍스트 "DRAFT"로 워터마크를 생성합니다.
watermark = WatermarkTextOptions("DRAFT")
```

### 또 보기
* class [`WatermarkTextOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/)
