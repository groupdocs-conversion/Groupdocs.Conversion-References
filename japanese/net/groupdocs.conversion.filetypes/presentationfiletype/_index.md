---
title: PresentationFileType
second_title: GroupDocs.Conversion for .NET API リファレンス
description: スライド図形テキストアニメーションビデオオーディオ埋め込みオブジェクトなどのプレゼンテーション データに対応するレコードのコレクションを格納するプレゼンテーション ファイル形式を定義します 次のファイル タイプが含まれます Odp./presentationfiletype/odp  Otp./presentationfiletype/otp  Pot./presentationfiletype/pot  Potm./presentationfiletype/potm  Potx./presentationfiletype/potx  Pps./presentationfiletype/pps  Ppsm./presentationfiletype/ppsm  Ppsx./presentationfiletype/ppsx  Ppt./presentationfiletype/ppt  Pptm./presentationfiletype/pptm  Pptx./presentationfiletype/pptx . プレゼンテーション形式の詳細ここhttps//wiki.fileformat.com/presentation.
type: docs
weight: 1020
url: /ja/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

スライド、図形、テキスト、アニメーション、ビデオ、オーディオ、埋め込みオブジェクトなどのプレゼンテーション データに対応するレコードのコレクションを格納するプレゼンテーション ファイル形式を定義します。 次のファイル タイプが含まれます: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Pptm`](./pptm) , [`Pptx`](./pptx) . プレゼンテーション形式の詳細[ここ](https://wiki.fileformat.com/presentation).

```csharp
public sealed class PresentationFileType : FileType
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | シリアル化コンストラクター |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | ファイルタイプの説明 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | ファイル拡張子 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | ファイル family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | ファイル形式 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 現在のオブジェクトを他のオブジェクトと比較します。 |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | 2 つのオブジェクト インスタンスが等しいかどうかを判断します。 |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 2 つのオブジェクト インスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | デフォルトのハッシュ関数として機能します。 |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 文字列表現 |

## 田畑

| 名前 | 説明 |
| --- | --- |
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | 拡張子が FODP のファイルは、OpenDocument フラット XML プレゼンテーションを表します。 OpenDocument 形式で保存されたプレゼンテーション ファイルですが、標準の .ODP ファイルで使用される .ZIP コンテナーではなく、フラットな XML 形式を使用して保存されます |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | ODP 拡張子を持つファイルは、OASISOpen 標準で OpenOffice.org が使用するプレゼンテーション ファイル形式を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/odp) |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | 拡張子が .OTP のファイルは、OASIS OpenDocument 標準形式のアプリケーションによって作成されたプレゼンテーション テンプレート ファイルを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/otp) |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | 拡張子が .POT のファイルは、PowerPoint 97-2003 バージョンで作成された Microsoft PowerPoint テンプレート ファイルを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/pot) |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | POTM 拡張子を持つファイルは、マクロをサポートする Microsoft PowerPoint テンプレート ファイルです。 POTM ファイルは PowerPoint 2007 以降で作成され、さらにプレゼンテーション ファイルを作成するために使用できる既定の設定が含まれています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/potm) |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | 拡張子が .POTX のファイルは、Microsoft PowerPoint 2007 以降で作成された Microsoft PowerPoint テンプレート プレゼンテーションを表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/potx) |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS、PowerPoint スライド ショー、ファイルは Microsoft PowerPoint を使用してスライド ショー用に作成されます。 PPS ファイルの読み取りと作成は、Microsoft PowerPoint 97-2003 でサポートされています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/pps) |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | PPSM 拡張子を持つファイルは、Microsoft PowerPoint 2007 以降で作成されたマクロ有効スライド ショー ファイル形式を表します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/ppsm) |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX、Power Point スライド ショー、ファイルは、スライド ショー用に Microsoft PowerPoint 2007 以降を使用して作成されます。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/ppsx) |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | 拡張子が PPT のファイルは、スライドショーとして表示するためのスライドのコレクションで構成される PowerPoint ファイルを表します。 Microsoft PowerPoint 97-2003 で使用されるバイナリ ファイル形式を指定します。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/ppt) |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | PPTM 拡張子を持つファイルは、Microsoft PowerPoint 2007 以降のバージョンで作成されたマクロ有効のプレゼンテーション ファイルです。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/pptm) |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | PPTX 拡張子を持つファイルは、一般的な Microsoft PowerPoint アプリケーションで作成されたプレゼンテーション ファイルです。バイナリであった以前のバージョンのプレゼンテーション ファイル形式 PPT とは異なり、PPTX 形式は Microsoft PowerPoint オープン XML プレゼンテーション ファイル形式に基づいています。 このファイル形式の詳細[ここ](https://wiki.fileformat.com/presentation/pptx) |

### 関連項目

* class [FileType](../filetype)
* 名前空間 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 組み立て [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
