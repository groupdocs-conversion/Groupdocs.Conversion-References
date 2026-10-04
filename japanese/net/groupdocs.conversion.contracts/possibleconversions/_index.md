---
title: "可能な変換"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "特定のソースファイル形式でサポートされる変換ペアを示すマッピングを表します"
type: docs
weight: 510
url: /ja/net/groupdocs.conversion.contracts/possibleconversions/
---
## PossibleConversions class

特定のソースファイル形式でサポートされる変換ペアを示すマッピングを表します

```csharp
public sealed class PossibleConversions : ValueObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [All](../../groupdocs.conversion.contracts/possibleconversions/all) { get; } | すべての対象ファイルタイプと一次/二次フラグの [`TargetConversion`](../targetconversion) の IEnumerable |
| [Item](../../groupdocs.conversion.contracts/possibleconversions/item) { get; } | 指定された対象ファイルタイプの対象変換を返します（インデクサー2つ） |
| [LoadOptions](../../groupdocs.conversion.contracts/possibleconversions/loadoptions) { get; } | 現在のタイプから変換するために使用できる事前定義されたロードオプション |
| [Primary](../../groupdocs.conversion.contracts/possibleconversions/primary) { get; } | 一次対象ファイルタイプ |
| [Secondary](../../groupdocs.conversion.contracts/possibleconversions/secondary) { get; } | 二次対象ファイルタイプ |
| [Source](../../groupdocs.conversion.contracts/possibleconversions/source) { get; } | ソースファイル形式 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [ValueObject](../valueobject)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
