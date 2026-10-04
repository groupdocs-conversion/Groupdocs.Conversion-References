---
title: "ICache"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "レンダリングされたドキュメントとドキュメントリソースのキャッシュを保存するために必要なメソッドを定義します。"
type: docs
weight: 20
url: /ja/net/groupdocs.conversion.caching/icache/
---
## ICache interface

レンダリングされたドキュメントとドキュメントリソースのキャッシュを保存するために必要なメソッドを定義します。

```csharp
public interface ICache
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetKeys](../../groupdocs.conversion.caching/icache/getkeys)(string) | フィルタに一致するすべてのキーを返します。 |
| [Set](../../groupdocs.conversion.caching/icache/set)(string, object) | キャッシュにエントリを挿入します。 |
| [TryGetValue](../../groupdocs.conversion.caching/icache/trygetvalue)(string, out object) | キーが存在する場合、そのエントリを取得します。 |

### 関連項目

* namespace [GroupDocs.Conversion.Caching](../../groupdocs.conversion.caching)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
