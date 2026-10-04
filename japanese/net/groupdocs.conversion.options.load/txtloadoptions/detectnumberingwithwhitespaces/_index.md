---
title: "DetectNumberingWithWhitespaces"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "プレーンテキスト文書が変換される際に、番号付きリスト項目がどのように認識されるかを指定できます。デフォルト値は true です。"
type: docs
weight: 30
url: /ja/net/groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces/
---
## TxtLoadOptions.DetectNumberingWithWhitespaces property

プレーンテキスト文書が変換される際に、番号付きリスト項目がどのように認識されるかを指定できます。デフォルト値は true です。

```csharp
public bool DetectNumberingWithWhitespaces { get; set; }
```

### 備考

このオプションが false に設定されている場合、リスト認識アルゴリズムはリスト番号がドット、右括弧、または箇条書き記号（例: \"•\", \"*\", \"-\", \"o\"）で終わるリスト段落を検出します。

このオプションが true に設定されている場合、空白文字もリスト番号の区切りとして使用されます。アラビア数字スタイルの番号付け（1., 1.1.2.）のリスト認識アルゴリズムは、空白文字とドット（\".\"）の両方を使用します。

### 関連項目

* class [TxtLoadOptions](../../txtloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
