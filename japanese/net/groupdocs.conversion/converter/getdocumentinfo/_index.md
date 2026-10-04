---
title: "GetDocumentInfo"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ソースドキュメント情報、ページ数、およびファイルタイプ固有のその他のドキュメントプロパティを取得します。"
type: docs
weight: 40
url: /ja/net/groupdocs.conversion/converter/getdocumentinfo/
---
## GetDocumentInfo() {#getdocumentinfo}

ソースドキュメント情報を取得します - ページ数やファイルタイプ固有のその他のドキュメントプロパティ。

```csharp
public IDocumentInfo GetDocumentInfo()
```

### 戻り値

ドキュメント情報は、[`IDocumentInfo`](../../../groupdocs.conversion.contracts/idocumentinfo) として取得できます。

### 備考

**Learn more**

* Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info](https://docs.groupdocs.com/display/conversionnet/Get+document+info)

### 関連項目

* interface [IDocumentInfo](../../../groupdocs.conversion.contracts/idocumentinfo)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## GetDocumentInfo&lt;T&gt;() {#getdocumentinfo_1}

ソースドキュメント情報を取得します - ページ数やファイルタイプ固有のその他のドキュメントプロパティ。

```csharp
public T GetDocumentInfo<T>()
    where T : IDocumentInfo
```

| パラメータ | 説明 |
| --- | --- |
| T | 特定のドキュメント情報型です。 |

### 戻り値

ドキュメント情報は、指定された型 T として取得されます。

### 備考

**Learn more**

* Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info](https://docs.groupdocs.com/display/conversionnet/Get+document+info)

### 関連項目

* interface [IDocumentInfo](../../../groupdocs.conversion.contracts/idocumentinfo)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
