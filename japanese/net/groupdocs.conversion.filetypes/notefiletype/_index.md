---
title: "NoteFileType"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Defines Notetaking formats. Includes the following file types One./notefiletype/one. Learn more about Notetaking formats herehttps//wiki.fileformat.com/notetaking."
type: docs
weight: 1180
url: /ja/net/groupdocs.conversion.filetypes/notefiletype/
---
## NoteFileType class

ノート取り形式を定義します。以下のファイルタイプが含まれます: [`One`](./one)。ノート取り形式の詳細は[こちら](https://wiki.fileformat.com/note-taking)をご覧ください。

```csharp
public sealed class NoteFileType : FileType
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [NoteFileType](notefiletype)() | シリアライズ コンストラクタ |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | ファイルタイプの説明 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | ファイル拡張子 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | ファイルファミリー |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | ファイル形式 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 現在のオブジェクトを他と比較します。 |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) を実装します。 |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | デフォルトのハッシュ関数として機能します。 |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 文字列表現 |

## Fields

| 名前 | 説明 |
| --- | --- |
| static readonly [One](../../groupdocs.conversion.filetypes/notefiletype/one) | .ONE 拡張子のファイルは Microsoft OneNote アプリケーションで作成されます。OneNote を使用すると、ドラフトパッドでメモを取るかのように情報を収集できます。このファイル形式の詳細は[こちら](https://wiki.fileformat.com/note-taking/one)をご覧ください。 |

### 関連項目

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
