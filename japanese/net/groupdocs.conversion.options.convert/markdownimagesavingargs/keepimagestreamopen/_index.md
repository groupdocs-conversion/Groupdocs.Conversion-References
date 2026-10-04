---
title: "KeepImageStreamOpen"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "false（デフォルト）の場合、コンバータは書き込み後に ImageStreamgroupdocs.conversion.options.convert/markdownimagesavingargs/imagestream を閉じます。これはディスクにフラッシュすべき FileStream の置き換えで慣例的な動作です。true に設定すると、変換完了後もストリームを開いたままにします。これは自分で読み取ることを想定した MemoryStream に典型的です。呼び出し側が破棄を管理します。"
type: docs
weight: 30
url: /ja/net/groupdocs.conversion.options.convert/markdownimagesavingargs/keepimagestreamopen/
---
## MarkdownImageSavingArgs.KeepImageStreamOpen property

false（デフォルト）の場合、コンバータは書き込み後に [`ImageStream`](../imagestream) を閉じます — これはディスクにフラッシュすべき FileStream の置き換えで慣例的な動作です。true に設定すると、変換完了後もストリームを開いたままにします（自分で読み取ることを想定した MemoryStream に典型的です）。呼び出し側が破棄を管理します。

```csharp
public bool KeepImageStreamOpen { get; set; }
```

### 関連項目

* class [MarkdownImageSavingArgs](../../markdownimagesavingargs)
* namespace [GroupDocs.Conversion.Options.Convert](../../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
