---
title: CadConvertOptions
second_title: GroupDocs.Conversion for .NET API リファレンス
description: CAD タイプへの変換オプション
type: docs
weight: 1430
url: /ja/net/groupdocs.conversion.options.convert/cadconvertoptions/
---
## CadConvertOptions class

CAD タイプへの変換オプション。

```csharp
public class CadConvertOptions : ConvertOptions<CadFileType>, IPagedConvertOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [CadConvertOptions](cadconvertoptions)() | の新しいインスタンスを初期化します[`CadConvertOptions`](../cadconvertoptions)class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | 入力ドキュメントを変換する必要がある目的のファイルの種類. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | 入力ドキュメントを変換する必要がある目的のファイルの種類. |
| [PageNumber](../../groupdocs.conversion.options.convert/cadconvertoptions/pagenumber) { get; set; } | 変換を開始するページ番号. |
| [PagesCount](../../groupdocs.conversion.options.convert/cadconvertoptions/pagescount) { get; set; } | から始まる変換するページ数`ページ番号`. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 現在のオプション インスタンスを複製します。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2 つのオブジェクト インスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2 つのオブジェクト インスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [CadFileType](../../groupdocs.conversion.filetypes/cadfiletype)
* interface [IPagedConvertOptions](../ipagedconvertoptions)
* 名前空間 [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* 組み立て [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->