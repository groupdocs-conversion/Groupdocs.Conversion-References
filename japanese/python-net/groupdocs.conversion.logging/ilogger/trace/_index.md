---
title: "trace メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "アプリケーションのフローに関する一般的に有用な情報を提供するトレースログメッセージを書き込みます。"
type: docs
url: /ja/python-net/groupdocs.conversion.logging/ilogger/trace/
is_root: false
weight: 1040
---


## trace {#message}

アプリケーションのフローに関する一般的に有用な情報を提供するトレースログメッセージを書き込みます。

```python
def trace(self, message):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| message | `str` | このトレース メッセージ。 |

### 例

```python
from groupdocs.conversion.logging import ConsoleLogger

logger = ConsoleLogger()
logger.trace("Conversion started")
```

### 関連項目
* class [`ILogger`](/conversion/python-net/groupdocs.conversion.logging/ilogger/)
