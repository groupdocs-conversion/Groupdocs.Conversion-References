---
title: "set_license メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "現在のプロセスにライセンスを適用します。"
type: docs
url: /ja/python-net/groupdocs.conversion/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

現在のプロセスにライセンスを適用します。

```python
def set_license(self, license_source):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| license_source |  | 文字列パスで指定された ``.lic`` ファイル、またはライセンスバイトを生成する読み取り可能な file‑like オブジェクトのいずれかです。file‑like 入力はブリッジに渡す前に一時ファイルに書き込まれます。 |

| 例外を発生させます | 説明 |
| :- | :- |
| `TypeError` | ``license_source`` が文字列パスでも読み取り可能な file‑like オブジェクトでもない場合。 |

### 関連項目
* class [`License`](/conversion/python-net/groupdocs.conversion/license/)
