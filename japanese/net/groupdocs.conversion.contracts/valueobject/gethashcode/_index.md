---
title: "GetHashCode"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "デフォルトのハッシュ関数として機能します。"
type: docs
weight: 20
url: /ja/net/groupdocs.conversion.contracts/valueobject/gethashcode/
---
## ValueObject.GetHashCode method

デフォルトのハッシュ関数として機能します。

```csharp
public override int GetHashCode()
```

### 戻り値

現在のオブジェクトのハッシュコード。

### 備考

配列、リスト、辞書の要素はその内容でハッシュ化され、等価性の比較方法と一致します。そのため、等価と判断される2つのオブジェクトは同じハッシュ値となり、辞書のキーやセットのメンバーとして使用できます。これは、他の IEnumerable である要素には適用されません。そのような要素は参照でハッシュ化され、遅延イテレータとして公開されている場合はアクセスのたびに異なる値を生成するため、これを保持するオブジェクトはキーとして使用できません。ネストされたコレクションも同様に、再帰的にではなく参照で比較・ハッシュ化されます。別の結果として、値オブジェクトが公開するコレクションを変更すると（ページリストへの追加やレイアウト名配列への書き込みなど）そのオブジェクトのハッシュが変わり、ハッシュコンテナに既に格納されているインスタンスが参照できなくなります。キーとして使用されたら、値オブジェクトは変更不可（凍結）として扱ってください。

### 関連項目

* class [ValueObject](../../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
