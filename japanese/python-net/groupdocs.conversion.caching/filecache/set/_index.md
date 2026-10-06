---
title: "set メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "キャッシュにエントリを挿入します。"
type: docs
url: /ja/python-net/groupdocs.conversion.caching/filecache/set/
is_root: false
weight: 1040
---


## set {#key-value}

キャッシュにエントリを挿入します。

```python
def set(self, key, value):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| key | `str` | キャッシュエントリの一意の識別子です。 |
| value | `Any` | 挿入するオブジェクト。 |

### 例

```python
from groupdocs.conversion import ConverterSettings, FileCache

# ファイルベースのキャッシュを使用したコンバータ設定を作成する
settings = ConverterSettings()
settings.cache = FileCache()

# キャッシュにオブジェクトを保存する
settings.cache.set("my_document", document)
```

### 関連項目
* class [`FileCache`](/conversion/python-net/groupdocs.conversion.caching/filecache/)
