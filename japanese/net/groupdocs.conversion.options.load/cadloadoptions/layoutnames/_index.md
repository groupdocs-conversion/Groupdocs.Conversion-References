---
title: "LayoutNames"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "変換対象となる CAD レイアウトを指定します"
type: docs
weight: 70
url: /ja/net/groupdocs.conversion.options.load/cadloadoptions/layoutnames/
---
## CadLoadOptions.LayoutNames property

変換対象となる CAD レイアウトを指定します

```csharp
public string[] LayoutNames { get; set; }
```

### 備考

PDF/UA-1 に変換する場合は尊重されません。そのターゲットは図面を単一のタグ付けページとして描画し、選択されたレイアウトごとにシートを保持できないため、代わりに図全体が変換され、ここでの設定は適用されません。PDF を含む他のすべてのターゲットは選択を尊重します。これらのターゲットでは、名前は図面が保持しているレイアウトと完全に一致させて照合されるため、大文字小文字の違いだけの名前は別の名前とみなされます。何も一致しない名前は除外され、呼び出し元はそのシートだけを失います。何も一致しない名前が含まれるリストは、[`InvalidLoadOptionsException`](../../../groupdocs.conversion.exceptions/invalidloadoptionsexception) をスローし、見逃した名前と図面が保持しているレイアウトを示します。呼び出し元が要求しなかったシートを描画することはありません。全くレイアウトを持たない図面は例外となり、名前が一致する対象がないため、何も拒否されません。

### 関連項目

* class [CadLoadOptions](../../cadloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
