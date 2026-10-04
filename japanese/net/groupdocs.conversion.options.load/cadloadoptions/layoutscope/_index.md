---
title: "LayoutScope"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "変換対象となる図面スペースを取得または設定します。デフォルトは Bothgroupdocs.conversion.options.load/cadlayoutscope/both で、変換を制限しません。LayoutNamesgroupdocs.conversion.options.load/cadloadoptions/layoutnames が指定されている場合は無視されます。これは明示的なレイアウト名が常に優先されるためです。null 値は Bothgroupdocs.conversion.options.load/cadlayoutscope/both とみなされます。"
type: docs
weight: 80
url: /ja/net/groupdocs.conversion.options.load/cadloadoptions/layoutscope/
---
## CadLoadOptions.LayoutScope property

変換対象となる図面スペースを取得または設定します。デフォルトは [`Both`](../../cadlayoutscope/both) で、変換を制限しません。[`LayoutNames`](../layoutnames) が指定されている場合は無視されます。これは明示的なレイアウト名が常に優先されるためです。`null` 値は [`Both`](../../cadlayoutscope/both) とみなされます。

```csharp
public CadLayoutScope LayoutScope { get; set; }
```

### 備考

図面が提供するシートのいずれも選択しないスコープは、[`InvalidLoadOptionsException`](../../../groupdocs.conversion.exceptions/invalidloadoptionsexception) をスローし、スコープと存在するシートの名前を示して変換に失敗します。スコープで除外されたスペースを描画することはありません。シートを全く提供しない図面は影響を受けず、単一ユニットとして変換されます。PDF/UA-1 に変換する場合は、[`LayoutNames`](../layoutnames) で示された理由により尊重されません。

### 関連項目

* class [CadLayoutScope](../../cadlayoutscope)
* class [CadLoadOptions](../../cadloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
