---
title: "trace 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "애플리케이션 흐름에 대한 일반적으로 유용한 정보를 제공하는 추적 로그 메시지를 기록합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.logging/ilogger/trace/
is_root: false
weight: 1040
---


## trace {#message}

애플리케이션 흐름에 대한 일반적으로 유용한 정보를 제공하는 추적 로그 메시지를 기록합니다.

```python
def trace(self, message):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| message | `str` | 추적 메시지. |

### 예제

```python
from groupdocs.conversion.logging import ConsoleLogger

logger = ConsoleLogger()
logger.trace("Conversion started")
```

### 또 보기
* class [`ILogger`](/conversion/python-net/groupdocs.conversion.logging/ilogger/)
