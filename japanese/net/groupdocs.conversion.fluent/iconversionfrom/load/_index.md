---
title: "ロード"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ソースドキュメントのファイル名を設定する"
type: docs
weight: 10
url: /ja/net/groupdocs.conversion.fluent/iconversionfrom/load/
---
## Load(string) {#load_2}

ソースドキュメントのファイル名を設定する

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string fileName)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileName | String | ソースドキュメント |

### 関連項目

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(string[]) {#load_3}

ソースドキュメント配列を設定する

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string[] fileName)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileName | String[] | ソースドキュメントのセット |

### 関連項目

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream&gt;) {#load_1}

ソースドキュメントのストリームを設定する

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream> documentStreamProvider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| documentStreamProvider | Func`1 | ソースドキュメントストリームプロバイダー |

### 例外

| 例外 | 条件 |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) | コンバータ設定の検証に失敗した場合、この例外がスローされます |

### 関連項目

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream[]&gt;) {#load}

ソースドキュメントのストリーム配列を設定する

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream[]> documentStreamProvider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| documentStreamProvider | Func`1 | ソースドキュメントストリームプロバイダー |

### 例外

| 例外 | 条件 |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) | コンバータ設定の検証に失敗した場合、この例外がスローされます |

### 関連項目

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
