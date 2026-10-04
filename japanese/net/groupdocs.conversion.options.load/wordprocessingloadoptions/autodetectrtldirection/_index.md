---
title: "AutoDetectRtlDirection"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "true の場合、デフォルトの段落およびテキストが主に右から左に向かうランは、変換前に bidi フラグが修正されます。これは Microsoft Word と LibreOffice が適用するヒューリスティックと一致し、特に Google Docs が ltwbidi/gt を付けず、RTL スクリプトのみを含むランに ltwrtl wval0/gt を付与した OOXML を生成する際の、アラビア語/ヘブライ語文書のレンダリングを修正します。false に設定すると、ソースマークアップの厳密な OOXML 解釈を保持します。"
type: docs
weight: 20
url: /ja/net/groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection/
---
## WordProcessingLoadOptions.AutoDetectRtlDirection property

true（既定）に設定すると、テキストが主に右から左へ向かう段落やランのバイディフラグが変換前に修正されます。これは Microsoft Word および LibreOffice が使用するヒューリスティックと一致し、&lt;w:bidi/&gt; がなく、RTL スクリプトのみを含むランに &lt;w:rtl w:val="0"/&gt; が付与された状態で生成された（特に Google Docs が生成する）アラビア語/ヘブライ語ドキュメントのレンダリングを修正します。false に設定すると、ソースマークアップの厳密な OOXML 解釈を保持します。

```csharp
public bool AutoDetectRtlDirection { get; set; }
```

### 関連項目

* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
