---
title: Convert
second_title: GroupDocs.Conversion for .NET API リファレンス
description: ソース ドキュメントを変換します変換されたドキュメント全体を保存します.
type: docs
weight: 20
url: /ja/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;Stream&gt;, ConvertOptions) {#convert}

ソース ドキュメントを変換します。変換されたドキュメント全体を保存します.

```csharp
public void Convert(Func<Stream> document, ConvertOptions convertOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`1 | 変換されたドキュメントをストリームに保存するデリゲート。 |
| convertOptions | ConvertOptions | 目的のターゲット ファイル タイプに固有の変換オプション。 |

### 備考

**もっと詳しく知る**

* ドキュメント変換の基本シナリオの詳細: [3 ステップでドキュメントを変換する方法](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 変換の使用例、高度な設定とカスタマイズ: [詳細設定でドキュメントを変換する](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_1}

ソース ドキュメントを変換します。変換されたドキュメント全体を保存します.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`1 | 変換されたドキュメントをストリームに保存するデリゲート。 |
| documentCompleted | Action`2 | 変換されたドキュメント stream. を受け取るデリゲート。ファイル コンテンツ ストリームファイルの名前 |
| convertOptions | ConvertOptions | 目的のターゲット ファイル タイプに固有の変換オプション。 |

### 備考

**もっと詳しく知る**

* ドキュメント変換の基本シナリオの詳細: [3 ステップでドキュメントを変換する方法](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 変換の使用例、高度な設定とカスタマイズ: [詳細設定でドキュメントを変換する](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_3}

ソース ドキュメントを変換します。変換されたドキュメント全体を保存します.

```csharp
public void Convert(Func<Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`1 | 変換されたドキュメントをストリームに保存するデリゲート。 |
| convertOptionsProvider | Func`3 | 変換オプション プロバイダー。変換ごとに呼び出され、特定の変換オプションを目的のターゲット ドキュメント タイプに提供します。 ファイルの名前ファイルのタイプ |

### 備考

**もっと詳しく知る**

* ドキュメント変換の基本シナリオの詳細: [3 ステップでドキュメントを変換する方法](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 変換の使用例、高度な設定とカスタマイズ: [詳細設定でドキュメントを変換する](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_2}

ソース ドキュメントを変換します。変換されたドキュメント全体を保存します.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`1 | 変換されたドキュメントをストリームに保存するデリゲート。 |
| documentCompleted | Action`2 | 変換されたドキュメント stream. を受け取るデリゲート。ファイル コンテンツ ストリームファイルの名前 |
| convertOptionsProvider | Func`3 | 変換オプション プロバイダー。変換ごとに呼び出され、特定の変換オプションを目的のターゲット ドキュメント タイプに提供します。 ファイルの名前ファイルのタイプ |

### 備考

**もっと詳しく知る**

* ドキュメント変換の基本シナリオの詳細: [3 ステップでドキュメントを変換する方法](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 変換の使用例、高度な設定とカスタマイズ: [詳細設定でドキュメントを変換する](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, ConvertOptions) {#convert_4}

ソース ドキュメントを変換します。変換されたドキュメント全体を保存します.

```csharp
public void Convert(Func<FileType, Stream> document, ConvertOptions convertOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`2 | 変換されたドキュメントをストリームに保存するデリゲート. ソースファイルのタイプ |
| convertOptions | ConvertOptions | 目的のターゲット ファイル タイプに固有の変換オプション。 |

### 備考

**もっと詳しく知る**

* ドキュメント変換の基本シナリオの詳細: [3 ステップでドキュメントを変換する方法](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 変換の使用例、高度な設定とカスタマイズ: [詳細設定でドキュメントを変換する](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_5}

ソース ドキュメントを変換します。変換されたドキュメント全体を保存します.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`2 | 変換されたドキュメントをストリームに保存するデリゲート. ソースファイルのタイプ |
| documentCompleted | Action`2 | 変換されたドキュメント stream. を受け取るデリゲート。ファイル コンテンツ ストリームファイルの名前 |
| convertOptions | ConvertOptions | 目的のターゲット ファイル タイプに固有の変換オプション。 |

### 備考

**もっと詳しく知る**

* ドキュメント変換の基本シナリオの詳細: [3 ステップでドキュメントを変換する方法](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 変換の使用例、高度な設定とカスタマイズ: [詳細設定でドキュメントを変換する](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_7}

ソース ドキュメントを変換します。変換されたドキュメント全体を保存します.

```csharp
public void Convert(Func<FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`2 | 変換されたドキュメントをストリームに保存するデリゲート. ソースファイルのタイプ |
| convertOptionsProvider | Func`3 | 変換オプション プロバイダー。変換ごとに呼び出され、特定の変換オプションを目的のターゲット ドキュメント タイプに提供します。 ファイルの名前ファイルのタイプ |

### 備考

**もっと詳しく知る**

* ドキュメント変換の基本シナリオの詳細: [3 ステップでドキュメントを変換する方法](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 変換の使用例、高度な設定とカスタマイズ: [詳細設定でドキュメントを変換する](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_6}

ソース ドキュメントを変換します。変換されたドキュメント全体を保存します.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`2 | 変換されたドキュメントをストリームに保存するデリゲート. ソースファイルのタイプ |
| documentCompleted | Action`2 | 変換されたドキュメント stream. を受け取るデリゲート。ファイル コンテンツ ストリームファイルの名前 |
| convertOptionsProvider | Func`3 | 変換オプション プロバイダー。変換ごとに呼び出され、特定の変換オプションを目的のターゲット ドキュメント タイプに提供します。 ファイルの名前ファイルのタイプ |

### 備考

**もっと詳しく知る**

* ドキュメント変換の基本シナリオの詳細: [3 ステップでドキュメントを変換する方法](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 変換の使用例、高度な設定とカスタマイズ: [詳細設定でドキュメントを変換する](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions) {#convert_16}

ソース ドキュメントを変換します。変換されたドキュメント全体を保存します.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| filePath | String | ソース ドキュメントへのファイル パス。 |
| convertOptions | ConvertOptions | 目的のターゲット ファイル タイプに固有の変換オプション。 |

### 備考

**もっと詳しく知る**

* ドキュメント変換の基本シナリオの詳細: [3 ステップでドキュメントを変換する方法](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 変換の使用例、高度な設定とカスタマイズ: [詳細設定でドキュメントを変換する](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, ConvertOptions) {#convert_8}

ソース ドキュメントを変換します。変換されたドキュメントをページごとに保存します.

```csharp
public void Convert(Func<int, Stream> document, ConvertOptions convertOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`2 | 変換されたドキュメントをストリームに保存するデリゲート. ページ番号 |
| convertOptions | ConvertOptions | 目的のターゲット ファイル タイプに固有の変換オプション。 |

### 備考

**もっと詳しく知る**

* ドキュメント変換の基本シナリオの詳細: [3 ステップでドキュメントを変換する方法](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 変換の使用例、高度な設定とカスタマイズ: [詳細設定でドキュメントを変換する](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_9}

ソース ドキュメントを変換します。変換されたドキュメントをページごとに保存します.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`2 | 変換されたドキュメント ページをストリームに保存するデリゲート。ページ番号 |
| documentCompleted | Action`3 | 変換されたドキュメント ページ ストリームを受け取るデリゲート。ページ番号ファイル コンテンツ ストリームファイルの名前 |
| convertOptions | ConvertOptions | 目的のターゲット ファイル タイプに固有の変換オプション。 |

### 備考

**もっと詳しく知る**

* ドキュメント変換の基本シナリオの詳細: [3 ステップでドキュメントを変換する方法](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 変換の使用例、高度な設定とカスタマイズ: [詳細設定でドキュメントを変換する](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_11}

ソース ドキュメントを変換します。変換されたドキュメントをページごとに保存します.

```csharp
public void Convert(Func<int, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`2 | 変換されたドキュメントをストリームに保存するデリゲート. ページ番号 |
| convertOptionsProvider | Func`3 | 変換オプション プロバイダー。変換ごとに呼び出され、特定の変換オプションを目的のターゲット ドキュメント タイプに提供します。 ファイルの名前ファイルのタイプ |

### 備考

**もっと詳しく知る**

* ドキュメント変換の基本シナリオの詳細: [3 ステップでドキュメントを変換する方法](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 変換の使用例、高度な設定とカスタマイズ: [詳細設定でドキュメントを変換する](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_10}

ソース ドキュメントを変換します。変換されたドキュメントをページごとに保存します.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`2 | 変換されたドキュメント ページをストリームに保存するデリゲート。ページ番号 |
| documentCompleted | Action`3 | 変換されたドキュメント ページ ストリームを受け取るデリゲート。ページ番号ファイル コンテンツ ストリームファイルの名前 |
| convertOptionsProvider | Func`3 | 変換オプション プロバイダー。変換ごとに呼び出され、特定の変換オプションを目的のターゲット ドキュメント タイプに提供します。 ファイルの名前ファイルのタイプ |

### 備考

**もっと詳しく知る**

* ドキュメント変換の基本シナリオの詳細: [3 ステップでドキュメントを変換する方法](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 変換の使用例、高度な設定とカスタマイズ: [詳細設定でドキュメントを変換する](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, ConvertOptions) {#convert_12}

ソース ドキュメントを変換します。変換されたドキュメントをページごとに保存します.

```csharp
public void Convert(Func<int, FileType, Stream> document, ConvertOptions convertOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`3 | 変換されたドキュメントをストリームに保存するデリゲート. ページ番号 |
| convertOptions | ConvertOptions | 目的のターゲット ファイル タイプに固有の変換オプション。 |

### 備考

**もっと詳しく知る**

* ドキュメント変換の基本シナリオの詳細: [3 ステップでドキュメントを変換する方法](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 変換の使用例、高度な設定とカスタマイズ: [詳細設定でドキュメントを変換する](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_13}

ソース ドキュメントを変換します。変換されたドキュメントをページごとに保存します.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, ConvertOptions convertOptions)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`3 | 変換されたドキュメント ページをストリームに保存するデリゲート。ページ番号ファイルの種類 |
| documentCompleted | Action`3 | 変換されたドキュメント ページ ストリームを受け取るデリゲート。ページ番号ファイル コンテンツ ストリームファイルの名前 |
| convertOptions | ConvertOptions | 目的のターゲット ファイル タイプに固有の変換オプション。 |

### 備考

**もっと詳しく知る**

* ドキュメント変換の基本シナリオの詳細: [3 ステップでドキュメントを変換する方法](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 変換の使用例、高度な設定とカスタマイズ: [詳細設定でドキュメントを変換する](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_15}

ソース ドキュメントを変換します。変換されたドキュメントをページごとに保存します.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`3 | 変換されたドキュメントをストリームに保存するデリゲート. ページ番号ファイルの種類 |
| convertOptionsProvider | Func`3 | 変換オプション プロバイダー。変換ごとに呼び出され、特定の変換オプションを目的のターゲット ドキュメント タイプに提供します。 ファイルの名前ファイルのタイプ |

### 備考

**もっと詳しく知る**

* ドキュメント変換の基本シナリオの詳細: [3 ステップでドキュメントを変換する方法](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 変換の使用例、高度な設定とカスタマイズ: [詳細設定でドキュメントを変換する](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_14}

ソース ドキュメントを変換します。変換されたドキュメントをページごとに保存します.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| document | Func`3 | 変換されたドキュメント ページをストリームに保存するデリゲート。ページ番号ファイルの種類 |
| documentCompleted | Action`3 | 変換されたドキュメント ページ ストリームを受け取るデリゲート。ページ番号ファイル コンテンツ ストリームファイルの名前 |
| convertOptionsProvider | Func`3 | 変換オプション プロバイダー。変換ごとに呼び出され、特定の変換オプションを目的のターゲット ドキュメント タイプに提供します。 ファイルの名前ファイルのタイプ |

### 備考

**もっと詳しく知る**

* ドキュメント変換の基本シナリオの詳細: [3 ステップでドキュメントを変換する方法](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* 変換の使用例、高度な設定とカスタマイズ: [詳細設定でドキュメントを変換する](https://docs.groupdocs.com/display/conversionnet/Converting)

### 関連項目

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* 名前空間 [GroupDocs.Conversion](../../converter)
* 組み立て [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
