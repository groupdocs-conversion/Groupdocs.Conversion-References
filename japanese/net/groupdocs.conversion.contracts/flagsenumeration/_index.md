---
title: "FlagsEnumeration"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ビットフラグ操作をサポートする列挙体を作成するための抽象基底クラスを表します。"
type: docs
weight: 220
url: /ja/net/groupdocs.conversion.contracts/flagsenumeration/
---
## FlagsEnumeration class

ビットフラグ操作をサポートする列挙体を作成するための抽象基底クラスを表します。

```csharp
public abstract class FlagsEnumeration : Enumeration
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 現在のオブジェクトを他と比較します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | デフォルトのハッシュ関数として機能します。 |
| virtual [HasFlag&lt;T&gt;](../../groupdocs.conversion.contracts/flagsenumeration/hasflag)(T) | 現在のフラグが指定されたフラグを持っているかチェックします。 |
| virtual [HasFlagValue](../../groupdocs.conversion.contracts/flagsenumeration/hasflagvalue)(int) | 現在のフラグが指定された値を持っているかチェックします。 |
| override [ToString](../../groupdocs.conversion.contracts/flagsenumeration/tostring)() | 現在のオブジェクトを文字列に変換します。 |
| static [Combine&lt;T&gt;](../../groupdocs.conversion.contracts/flagsenumeration/combine)(T, T) | 2つのフラグ列挙体を1つに結合します。 |

### 関連項目

* class [Enumeration](../enumeration)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
