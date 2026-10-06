---
title: "get_hash_code メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "デフォルトのハッシュ関数として機能します。"
type: docs
url: /ja/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/
is_root: false
weight: 1040
---


## get_hash_code

デフォルトのハッシュ関数として機能します。

配列、リスト、辞書のコンポーネントはその内容に基づいてハッシュ化され、等価性の比較方法と一致するため、等価と判断される 2 つのオブジェクトは同じハッシュ値となり、辞書のキーやセットのメンバーとして使用できます。

これは、`System.Collections.IEnumerable` のような別のコンポーネントには適用されません。そのようなコンポーネントは参照によってハッシュ化され、遅延イテレータとして公開されたものはアクセスのたびに異なる値を生成するため、これを保持するオブジェクトはキーとして全く使用できません。入れ子のコレクションも同様に、再帰的にではなく参照で比較およびハッシュ化されます。

もう一つの結果として、値オブジェクトが参照するコレクションを変更すると（例：ページリストへの追加やレイアウト名配列への書き込み）、そのオブジェクトのハッシュが変わり、ハッシュコンテナに既に格納されているインスタンスが参照できなくなります。キーとして使用されたら、値オブジェクトは凍結されたものとして扱ってください。

```python
def get_hash_code(self):
    ...
```

**Returns:** A hash code for the current object.

### 関連項目
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)
