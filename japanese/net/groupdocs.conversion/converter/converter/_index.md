---
title: "Converter"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Convertergroupdocs.conversion/converter クラスの新しいインスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor}

[`Converter`](../../converter) クラスの新しいインスタンスを初期化します。

```csharp
public Converter(Func<Stream> sourceStreamProvider)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | 読み取り可能なストリームを返すメソッド。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceStreamProvider* が null のときにスローされます。 |

### 備考

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 関連項目

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_1}

[`Converter`](../../converter) クラスの新しいインスタンスを初期化します。

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | 読み取り可能なストリームを返すメソッド。 |
| settings | Func`1 | Converter の設定。 |

### 備考

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 関連項目

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_3}

[`Converter`](../../converter) クラスの新しいインスタンスを初期化します。

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | 読み取り可能なストリームを返すメソッド。 |
| loadOptions | Func`2 | ドキュメントのロードオプションを提供するデリゲート。シグネチャ: `Func<LoadContext, LoadOptions>`。[`LoadContext`](../../loadcontext) パラメータは、ロード中のドキュメントに関する情報を含みます。 |
| settings | Func`1 | Converter の設定。 |

### 備考

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 関連項目

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_4}

明示的な変換イベントを使用して、[`Converter`](../../converter) クラスの新しいインスタンスを初期化します。

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | 読み取り可能なストリームを返すメソッド。 |
| loadOptions | Func`2 | ドキュメントのロードオプションを提供するデリゲート。 |
| settings | Func`1 | Converter の設定。 |
| events | Func`1 | コンバータのライフタイム中に登録された集約された [`ConversionEvents`](../../conversionevents) を提供するデリゲート。 |

### 関連項目

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_2}

明示的な変換イベントを使用して、[`Converter`](../../converter) クラスの新しいインスタンスを初期化します。

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings, 
    Func<ConversionEvents> events)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | 読み取り可能なストリームを返すメソッド。 |
| settings | Func`1 | Converter の設定。 |
| events | Func`1 | コンバータのライフタイム中に登録された集約された [`ConversionEvents`](../../conversionevents) を提供するデリゲート。 |

### 関連項目

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_5}

[`Converter`](../../converter) クラスの新しいインスタンスを初期化します。

```csharp
public Converter(string filePath)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filePath | String | ソースドキュメントへのファイルパス。 |

### 備考

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 関連項目

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_6}

[`Converter`](../../converter) クラスの新しいインスタンスを初期化します。

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filePath | String | ソースドキュメントへのファイルパス。 |
| settings | Func`1 | Converter の設定。 |

### 備考

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 関連項目

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_8}

[`Converter`](../../converter) クラスの新しいインスタンスを初期化します。

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filePath | String | ソースドキュメントへのファイルパス。 |
| loadOptions | Func`2 | ドキュメントのロードオプションを提供するデリゲート。シグネチャ: `Func<LoadContext, LoadOptions>`。[`LoadContext`](../../loadcontext) パラメータは、ロード中のドキュメントに関する情報を含みます。 |
| settings | Func`1 | Converter の設定。 |

### 備考

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 関連項目

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_9}

明示的な変換イベントを使用して、[`Converter`](../../converter) クラスの新しいインスタンスを初期化します。

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filePath | String | ソースドキュメントへのファイルパス。 |
| loadOptions | Func`2 | ドキュメントのロードオプションを提供するデリゲート。 |
| settings | Func`1 | Converter の設定。 |
| events | Func`1 | コンバータのライフタイム中に登録された集約された [`ConversionEvents`](../../conversionevents) を提供するデリゲート。 |

### 関連項目

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_7}

明示的な変換イベントを使用して、[`Converter`](../../converter) クラスの新しいインスタンスを初期化します。

```csharp
public Converter(string filePath, Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filePath | String | ソースドキュメントへのファイルパス。 |
| settings | Func`1 | Converter の設定。 |
| events | Func`1 | コンバータのライフタイム中に登録された集約された [`ConversionEvents`](../../conversionevents) を提供するデリゲート。 |

### 関連項目

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
