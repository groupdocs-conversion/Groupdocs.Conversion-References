---
title: "FileType"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ファイルタイプの基底クラス"
type: docs
weight: 1130
url: /ja/net/groupdocs.conversion.filetypes/filetype/
---
## FileType class

ファイルタイプの基底クラス

```csharp
public class FileType : Enumeration
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [FileType](filetype)() | シリアライズ コンストラクタ |

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
| static [FromExtension](../../groupdocs.conversion.filetypes/filetype/fromextension)(string) | Gets FileType for provided fileExtension |
| static [FromFilename](../../groupdocs.conversion.filetypes/filetype/fromfilename)(string) | Returns FileType for specified fileName |
| static [FromStream](../../groupdocs.conversion.filetypes/filetype/fromstream)(Stream) | Returns FileType for provided document stream |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 現在のオブジェクトを他と比較します。 |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals#equals)(Enumeration) | [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) を実装します。 |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | デフォルトのハッシュ関数として機能します。 |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 文字列表現 |
| static [GetAll&lt;T&gt;](../../groupdocs.conversion.filetypes/filetype/getall)() | Returns all enumeration values. |
| [implicit operator](../../groupdocs.conversion.filetypes/filetype/op_implicit) | Implicit conversion to string |

## Fields

| 名前 | 説明 |
| --- | --- |
| static readonly [Unknown](../../groupdocs.conversion.filetypes/filetype/unknown) | Unknown file type |

### 関連項目

* class [Enumeration](../../groupdocs.conversion.contracts/enumeration)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
