---
title: "IConversionSettings"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Load の前のエントリーステージで変換設定またはイベントを設定します。"
type: docs
weight: 1540
url: /ja/net/groupdocs.conversion.fluent/iconversionsettings/
---
## IConversionSettings interface

`Load` の前のエントリーステージで変換設定またはイベントを設定します。

```csharp
public interface IConversionSettings
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [WithEvents](../../groupdocs.conversion.fluent/iconversionsettings/withevents)(Action&lt;ConversionEvents&gt;) | コンバータのライフタイム全体で存続し、各変換実行時に発火する [`ConversionEvents`](../../groupdocs.conversion/conversionevents) バッグに変換ライフサイクルイベントハンドラを登録します。[`WithSettings`](./withsettings) と同じエントリーステージに位置します。複数回の呼び出しは蓄積され、同じ内部バッグが各 *configure* アクションに渡されるため、以前の呼び出しで設定されたハンドラは後の呼び出しで上書きされない限り残ります。 |
| [WithSettings](../../groupdocs.conversion.fluent/iconversionsettings/withsettings)(Func&lt;ConverterSettings&gt;) | コンバータ設定を設定する |

### 関連項目

* namespace [GroupDocs.Conversion.Fluent](../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
