---
title: "ロード"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "変換用のソースドキュメントを構成する"
type: docs
weight: 10
url: /ja/net/groupdocs.conversion/fluentconverter/load/
---
## Load(string) {#load_2}

変換用のソースドキュメントを構成する

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(string fileName)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileName | String | ソースドキュメント |

### 関連項目

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(string[]) {#load_3}

ソースドキュメントのセットを構成する

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(string[] fileName)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fileName | String[] | ソースファイルの配列 |

### 関連項目

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream&gt;) {#load_1}

ソースドキュメントのストリームを構成する

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream> documentStreamProvider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| documentStreamProvider | Func`1 | ソースドキュメントストリームプロバイダー |

### 関連項目

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream[]&gt;) {#load}

ソースドキュメントストリームのセットを構成する

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(
    Func<Stream[]> documentStreamProvider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| documentStreamProvider | Func`1 | ソースドキュメントストリームのプロバイダーのセット |

### 関連項目

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
