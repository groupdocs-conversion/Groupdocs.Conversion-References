---
title: Converter
second_title: GroupDocs.Conversion for .NET API リファレンス
description: の新しいインスタンスを初期化しますConvertergroupdocs.conversion/converterclass.
type: docs
weight: 10
url: /ja/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor_1}

の新しいインスタンスを初期化します[`Converter`](../../converter)class.

```csharp
public Converter(Func<Stream> document)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`1 | 読み取り可能なストリームを返すメソッド。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | スローされるタイミング*document*無効である。 |

### 備考

**もっと詳しく知る**

* FTP、Amazon S3 ストレージ、Windows Azure、またはその他のサードパーティ ストレージに保存されているドキュメントを読み込んで変換する方法の詳細: [さまざまなソースからのドキュメントの読み込み](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* ファイル タイプに応じたドキュメント読み込みオプションの詳細: [さまざまなドキュメント タイプの読み込みオプション](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 関連項目

* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_2}

の新しいインスタンスを初期化します[`Converter`](../../converter)class.

```csharp
public Converter(Func<Stream> document, Func<ConverterSettings> settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`1 | 読み取り可能なストリームを返すメソッド。 |
| settings | Func`1 | コンバーターの設定。 |

### 備考

**もっと詳しく知る**

* FTP、Amazon S3 ストレージ、Windows Azure、またはその他のサードパーティ ストレージに保存されているドキュメントを読み込んで変換する方法の詳細: [さまざまなソースからのドキュメントの読み込み](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* ファイル タイプに応じたドキュメント読み込みオプションの詳細: [さまざまなドキュメント タイプの読み込みオプション](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 関連項目

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_3}

の新しいインスタンスを初期化します[`Converter`](../../converter)class.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`1 | 読み取り可能なストリームを返すメソッド。 |
| loadOptions | Func`1 | ドキュメント読み込みオプションを返すメソッド。 |

### 備考

**もっと詳しく知る**

* FTP、Amazon S3 ストレージ、Windows Azure、またはその他のサードパーティ ストレージに保存されているドキュメントを読み込んで変換する方法の詳細: [さまざまなソースからのドキュメントの読み込み](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* ファイル タイプに応じたドキュメント読み込みオプションの詳細: [さまざまなドキュメント タイプの読み込みオプション](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 関連項目

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_4}

の新しいインスタンスを初期化します[`Converter`](../../converter)class.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`1 | 読み取り可能なストリームを返すメソッド。 |
| loadOptions | Func`1 | ドキュメント読み込みオプションを返すメソッド。 |
| settings | Func`1 | コンバーターの設定。 |

### 備考

**もっと詳しく知る**

* FTP、Amazon S3 ストレージ、Windows Azure、またはその他のサードパーティ ストレージに保存されているドキュメントを読み込んで変換する方法の詳細: [さまざまなソースからのドキュメントの読み込み](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* ファイル タイプに応じたドキュメント読み込みオプションの詳細: [さまざまなドキュメント タイプの読み込みオプション](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 関連項目

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) {#constructor_5}

の新しいインスタンスを初期化します[`Converter`](../../converter)class.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`1 | 読み取り可能なストリームを返すメソッド。 |
| loadOptions | Func`2 | ドキュメント読み込みオプションを返すメソッド. ソースファイルのタイプ |

### 備考

**もっと詳しく知る**

* FTP、Amazon S3 ストレージ、Windows Azure、またはその他のサードパーティ ストレージに保存されているドキュメントを読み込んで変換する方法の詳細: [さまざまなソースからのドキュメントの読み込み](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* ファイル タイプに応じたドキュメント読み込みオプションの詳細: [さまざまなドキュメント タイプの読み込みオプション](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 関連項目

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_6}

の新しいインスタンスを初期化します[`Converter`](../../converter)class.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`1 | 読み取り可能なストリームを返すメソッド。 |
| loadOptions | Func`2 | ドキュメント読み込みオプションを返すメソッド. ソースファイルのタイプ |
| settings | Func`1 | コンバーターの設定。 |

### 備考

**もっと詳しく知る**

* FTP、Amazon S3 ストレージ、Windows Azure、またはその他のサードパーティ ストレージに保存されているドキュメントを読み込んで変換する方法の詳細: [さまざまなソースからのドキュメントの読み込み](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* ファイル タイプに応じたドキュメント読み込みオプションの詳細: [さまざまなドキュメント タイプの読み込みオプション](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 関連項目

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_7}

の新しいインスタンスを初期化します[`Converter`](../../converter)class.

```csharp
public Converter(string filePath)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ソース ドキュメントへのファイル パス。 |

### 備考

**もっと詳しく知る**

* FTP、Amazon S3 ストレージ、Windows Azure、またはその他のサードパーティ ストレージに保存されているドキュメントを読み込んで変換する方法の詳細: [さまざまなソースからのドキュメントの読み込み](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* ファイル タイプに応じたドキュメント読み込みオプションの詳細: [さまざまなドキュメント タイプの読み込みオプション](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 関連項目

* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_8}

の新しいインスタンスを初期化します[`Converter`](../../converter)class.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ソース ドキュメントへのファイル パス。 |
| settings | Func`1 | コンバーターの設定。 |

### 備考

**もっと詳しく知る**

* FTP、Amazon S3 ストレージ、Windows Azure、またはその他のサードパーティ ストレージに保存されているドキュメントを読み込んで変換する方法の詳細: [さまざまなソースからのドキュメントの読み込み](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* ファイル タイプに応じたドキュメント読み込みオプションの詳細: [さまざまなドキュメント タイプの読み込みオプション](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 関連項目

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;) {#constructor_9}

の新しいインスタンスを初期化します[`Converter`](../../converter)class.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ソース ドキュメントへのファイル パス。 |
| loadOptions | Func`1 | ドキュメント読み込みオプションを返すメソッド。 |

### 備考

**もっと詳しく知る**

* FTP、Amazon S3 ストレージ、Windows Azure、またはその他のサードパーティ ストレージに保存されているドキュメントを読み込んで変換する方法の詳細: [さまざまなソースからのドキュメントの読み込み](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* ファイル タイプに応じたドキュメント読み込みオプションの詳細: [さまざまなドキュメント タイプの読み込みオプション](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 関連項目

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_10}

の新しいインスタンスを初期化します[`Converter`](../../converter)class.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions, Func<ConverterSettings> settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ソース ドキュメントへのファイル パス。 |
| loadOptions | Func`1 | ドキュメント読み込みオプションを返すメソッド。 |
| settings | Func`1 | コンバーターの設定。 |

### 備考

**もっと詳しく知る**

* FTP、Amazon S3 ストレージ、Windows Azure、またはその他のサードパーティ ストレージに保存されているドキュメントを読み込んで変換する方法の詳細: [さまざまなソースからのドキュメントの読み込み](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* ファイル タイプに応じたドキュメント読み込みオプションの詳細: [さまざまなドキュメント タイプの読み込みオプション](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 関連項目

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;) {#constructor_11}

の新しいインスタンスを初期化します[`Converter`](../../converter)class.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ソース ドキュメントへのファイル パス。 |
| loadOptions | Func`2 | ドキュメント読み込みオプションを返すメソッド. ソースファイルのタイプ |

### 備考

**もっと詳しく知る**

* FTP、Amazon S3 ストレージ、Windows Azure、またはその他のサードパーティ ストレージに保存されているドキュメントを読み込んで変換する方法の詳細: [さまざまなソースからのドキュメントの読み込み](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* ファイル タイプに応じたドキュメント読み込みオプションの詳細: [さまざまなドキュメント タイプの読み込みオプション](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 関連項目

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_12}

の新しいインスタンスを初期化します[`Converter`](../../converter)class.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ソース ドキュメントへのファイル パス。 |
| loadOptions | Func`2 | ドキュメント読み込みオプションを返すメソッド. ソースファイルのタイプ |
| settings | Func`1 | コンバーターの設定。 |

### 備考

**もっと詳しく知る**

* FTP、Amazon S3 ストレージ、Windows Azure、またはその他のサードパーティ ストレージに保存されているドキュメントを読み込んで変換する方法の詳細: [さまざまなソースからのドキュメントの読み込み](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* ファイル タイプに応じたドキュメント読み込みオプションの詳細: [さまざまなドキュメント タイプの読み込みオプション](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 関連項目

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Converter() {#constructor}

の新しいインスタンスを初期化します[`Converter`](../../converter)流暢な変換設定のクラス.

```csharp
public Converter()
```

### 備考

流暢な変換の使用例:

```csharp
var converter = new Converter();
```

```csharp
converter
    .Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
converter
    .WithSettings(() => new ConverterSettings())
    .Load("").WithOptions(new PdfLoadOptions())
    .ConvertTo("").WithOptions(new PdfConvertOptions())
    .OnConversionCompleted(convertedDocumentStream => { })
    .Convert();
```

```csharp
converter
    .Load("").WithOptions(new PdfLoadOptions())
    .ConvertByPageTo((number => new FileStream("", FileMode.Create))).WithOptions(new PdfConvertOptions())
    .OnConversionCompleted((number, stream) => {})
    .Convert();
```

```csharp
converter.Load("").GetPossibleConversions();
converter.Load("").GetDocumentInfo();
converter.Load("").WithOptions(new PdfLoadOptions()).GetPossibleConversions();
converter.Load("").WithOptions(new PdfLoadOptions()).GetDocumentInfo();
```

### 関連項目

* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
