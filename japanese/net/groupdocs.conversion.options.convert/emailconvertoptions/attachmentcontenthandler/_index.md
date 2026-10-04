---
title: "AttachmentContentHandler"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "メール添付ファイルのカスタム処理を行うデリゲートです。デリゲートは添付ファイル名、コンテンツタイプ、元の添付ストリームをパラメータとして受け取り、変更された添付ストリームを返します。"
type: docs
weight: 20
url: /ja/net/groupdocs.conversion.options.convert/emailconvertoptions/attachmentcontenthandler/
---
## EmailConvertOptions.AttachmentContentHandler property

メール添付ファイルのカスタム処理を扱うデリゲートです。デリゲートは添付ファイル名、コンテンツタイプ、元の添付ストリームをパラメーターとして受け取り、変更された添付ストリームを返します。

```csharp
public Func<string, string, Stream, Stream> AttachmentContentHandler { get; set; }
```

### 関連項目

* class [EmailConvertOptions](../../emailconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
