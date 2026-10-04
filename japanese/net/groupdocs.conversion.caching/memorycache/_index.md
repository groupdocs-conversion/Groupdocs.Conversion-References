---
title: "MemoryCache"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "メモリキャッシュの動作です。キャッシュがメモリに保存されることを意味します。"
type: docs
weight: 30
url: /ja/net/groupdocs.conversion.caching/memorycache/
---
## MemoryCache class

メモリキャッシュの動作です。キャッシュがメモリに保存されることを意味します。

```csharp
public sealed class MemoryCache : ICache
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [MemoryCache](memorycache)() | MemoryCache クラスの新しいインスタンスを作成します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetKeys](../../groupdocs.conversion.caching/memorycache/getkeys)(string) | フィルタに一致するすべてのキーを返します。 |
| [Set](../../groupdocs.conversion.caching/memorycache/set)(string, object) | キャッシュにエントリを挿入します。 |
| [TryGetValue](../../groupdocs.conversion.caching/memorycache/trygetvalue)(string, out object) | キーが存在する場合、そのエントリを取得します。 |

### 備考

**Learn more**

* More about caching and optimizing conversion process performance: [Caching conversion results](https://docs.groupdocs.com/display/conversionnet/Caching)

### 関連項目

* interface [ICache](../icache)
* namespace [GroupDocs.Conversion.Caching](../../groupdocs.conversion.caching)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
