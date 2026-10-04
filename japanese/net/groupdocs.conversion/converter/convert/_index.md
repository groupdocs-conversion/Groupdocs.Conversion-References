---
title: "Convert"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ソースドキュメントを変換します。変換されたドキュメント全体を保存します。"
type: docs
weight: 20
url: /ja/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_4}

ソースドキュメントを変換します。変換されたドキュメント全体を保存します。

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| targetStreamProvider | Func`2 | 変換されたドキュメントをストリームに保存するデリゲートです。 |
| convertOptions | ConvertOptions | 目的のターゲットファイルタイプに固有の変換オプションです。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 備考

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [SaveContext](../../savecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert}

ソースドキュメントを変換します。変換されたドキュメント全体を保存します。

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| convertOptions | ConvertOptions | 目的のターゲットファイルタイプに固有の変換オプションです。 |
| documentCompleted | Action`1 | 変換されたドキュメントストリームを受け取るデリゲート。シグネチャ: `Action<ConvertedContext>`。[`ConvertedContext`](../../convertedcontext) パラメータは、変換されたドキュメントストリームとメタデータを含みます。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 備考

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_5}

ソースドキュメントを変換します。変換されたドキュメント全体を保存します。

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| targetStreamProvider | Func`2 | 変換されたドキュメントを保存するためのストリームを提供するデリゲート。シグネチャ: `Func<SaveContext, Stream>`。[`SaveContext`](../../savecontext) パラメータは、保存操作に関する情報を含みます。 |
| convertOptionsProvider | Func`2 | 変換オプションを提供するデリゲート。シグネチャ: `Func<ConvertContext, ConvertOptions>`。[`ConvertContext`](../../convertcontext) パラメータは、変換操作に関する情報を含みます。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 備考

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [SaveContext](../../savecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert_2}

ソースドキュメントを変換します。変換されたドキュメント全体を保存します。

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedContext> documentCompleted, CancellationToken cancellationToken = default)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | 変換オプションを提供するデリゲート。シグネチャ: `Func<ConvertContext, ConvertOptions>`。[`ConvertContext`](../../convertcontext) パラメータは、変換操作に関する情報を含みます。 |
| documentCompleted | Action`1 | 変換されたドキュメントストリームを受け取るデリゲート。シグネチャ: `Action<ConvertedContext>`。[`ConvertedContext`](../../convertedcontext) パラメータは、変換されたドキュメントストリームとメタデータを含みます。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 備考

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions, CancellationToken) {#convert_8}

ソースドキュメントを変換します。変換されたドキュメント全体を保存します。

```csharp
public void Convert(string filePath, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filePath | String | ソースドキュメントへのファイルパス。 |
| convertOptions | ConvertOptions | 目的のターゲットファイルタイプに固有の変換オプションです。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 備考

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_7}

ソースドキュメントを変換します。変換されたドキュメントをページ単位で保存します。

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| targetStreamProvider | Func`2 | 各変換ページを保存するためのストリームを提供するデリゲート。シグネチャ: `Func<SavePageContext, Stream>`。[`SavePageContext`](../../savepagecontext) パラメータは、ページ番号とドキュメント情報を含みます。 |
| convertOptionsProvider | Func`2 | 変換オプションを提供するデリゲート。シグネチャ: `Func<ConvertContext, ConvertOptions>`。[`ConvertContext`](../../convertcontext) パラメータは、変換操作に関する情報を含みます。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 備考

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [SavePageContext](../../savepagecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_6}

ソースドキュメントを変換します。変換されたドキュメントをページ単位で保存します。

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    ConvertOptions convertOptions, CancellationToken cancellationToken = default)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| targetStreamProvider | Func`2 | 各変換ページを保存するためのストリームを提供するデリゲート。シグネチャ: `Func<SavePageContext, Stream>`。[`SavePageContext`](../../savepagecontext) パラメータは、ページ番号とドキュメント情報を含みます。 |
| convertOptions | ConvertOptions | 目的のターゲットファイルタイプに固有の変換オプションです。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 備考

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [SavePageContext](../../savepagecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_1}

ソースドキュメントを変換します。変換されたドキュメントをページ単位で保存します。

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedPageContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| documentCompleted | ConvertOptions | 各変換ページを受け取るデリゲート。シグネチャ: `Action<ConvertedPageContext>`。[`ConvertedPageContext`](../../convertedpagecontext) パラメータは、ページ番号、ストリーム、ソースファイル名、ターゲットファイルタイプを含みます。 |
| convertOptions | Action`1 | 目的のターゲットファイルタイプに固有の変換オプションです。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 備考

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_3}

ソースドキュメントを変換します。変換されたドキュメントをページ単位で保存します。

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedPageContext> documentCompleted, CancellationToken cancellationToken = default)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | 変換オプションを提供するデリゲート。シグネチャ: `Func<ConvertContext, ConvertOptions>`。[`ConvertContext`](../../convertcontext) パラメータは、変換操作に関する情報を含みます。 |
| documentCompleted | Action`1 | 各変換ページを受け取るデリゲート。シグネチャ: `Action<ConvertedPageContext>`。[`ConvertedPageContext`](../../convertedpagecontext) パラメータは、ページ番号、ストリーム、ソースファイル名、ターゲットファイルタイプを含みます。 |
| cancellationToken | CancellationToken | キャンセルトークンです。 |

### 備考

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
