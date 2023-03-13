---
title: CompressionFileType
second_title: GroupDocs.Conversion for .NET API リファレンス
description: 圧縮形式を定義します次のファイル タイプが含まれます Zip./compressionfiletype/zip. Rar./compressionfiletype/rar. SevenZ./compressionfiletype/sevenz. Tar./compressionfiletype/tar. Gz./compressionfiletype/gz. Gzip./compressionfiletype/gzip. Bz2./compressionfiletype/bz2 . 圧縮形式の詳細ここhttps//docs.fileformat.com/compression/.
type: docs
weight: 870
url: /ja/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

圧縮形式を定義します。次のファイル タイプが含まれます: [`Zip`](./zip). [`Rar`](./rar). [`SevenZ`](./sevenz). [`Tar`](./tar). [`Gz`](./gz). [`Gzip`](./gzip). [`Bz2`](./bz2) . 圧縮形式の詳細[ここ](https://docs.fileformat.com/compression/).

```csharp
public sealed class CompressionFileType : FileType
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [CompressionFileType](compressionfiletype)() | シリアル化コンストラクター |

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
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 は、BZIP2 オープン ソース圧縮方式を使用して生成された圧縮ファイルで、ほとんどが UNIX または Linux システムで使用されます。単一のファイルの圧縮に使用され、複数のファイルのアーカイブには使用されません。 このファイル形式の詳細[ここ](https://docs.fileformat.com/compression/bz2/) |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | 拡張子が .cab のファイルは、システム ファイルのカテゴリに属する Windows キャビネット ファイルに属します。これは、LZX、Quantum、ZIP などの圧縮データ アルゴリズムをサポートするバージョンの Microsoft Windows でアーカイブ ファイル形式で保存されるファイルです。 このファイル形式の詳細[ここ](https://docs.fileformat.com/system/cab/) |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio は、一般的なファイル アーカイバ ユーティリティとそれに関連するファイル形式です。主に Unix ライクなコンピュータ オペレーティング システムにインストールされます。 |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | GZ ファイルは、標準の gzip (GNU zip) 圧縮アルゴリズムを使用して作成された圧縮アーカイブです。複数の圧縮ファイル、ディレクトリ、およびファイル スタブが含まれる場合があります。 このファイル形式の詳細[ここ](https://docs.fileformat.com/compression/gz/) |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Gzip ファイルは、標準の gzip (GNU zip) 圧縮アルゴリズムを使用して作成された圧縮アーカイブです。複数の圧縮ファイル、ディレクトリ、およびファイル スタブが含まれる場合があります。 このファイル形式の詳細[ここ](https://docs.fileformat.com/compression/gz/) |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | 拡張子が .lz のファイルは、圧縮用の無料のコマンドライン ツールである Lzip で作成された圧縮アーカイブ ファイルです。サポート ファイルを圧縮するための連結をサポートしています。 LZ ファイルのメディア タイプは application/lzip で、BZ2. よりも高い圧縮率をサポートします。このファイル形式の詳細[ここ](https://docs.fileformat.com/compression/bz2/) |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | 拡張子が .lzma のファイルは、LZMA (Lempel-Ziv-Markov chain Algorithm) 圧縮方式を使用して作成された圧縮アーカイブ ファイルです。これらは主に Unix オペレーティング システムで検出/使用され、ファイル サイズを最小化するための ZIP などの他の圧縮アルゴリズムに似ています。 このファイル形式の詳細[ここ](https://docs.fileformat.com/compression/lzma/) |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | 拡張子が .rar のファイルは、情報を圧縮または通常の形式で保存するために作成されたアーカイブ ファイルです。 Roshal ARchive ファイル形式の略である RAR. このファイル形式の詳細[ここ](https://docs.fileformat.com/compression/rar/) |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z は、ファイルやフォルダーを高圧縮率で圧縮するためのアーカイブ形式です。オープン ソース アーキテクチャに基づいているため、あらゆる圧縮および暗号化アルゴリズムを使用できます。 このファイル形式の詳細[ここ](https://docs.fileformat.com/compression/7z/) |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | 拡張子が .tar のファイルは、1 つまたは複数のファイルを収集するための Unix ベースのユーティリティで作成されたアーカイブです。複数のファイルが非圧縮形式で保存され、アーカイブへのファイルとフォルダーの追加がサポートされます。 このファイル形式の詳細[ここ](https://docs.fileformat.com/compression/tar/) |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ は、LZMA2 圧縮アルゴリズムを利用する圧縮ファイル形式です。これは、一般的な gzip および bzip2 形式の代替として設計されており、これらの古い標準よりも多くの利点があります. このファイル形式について詳しく知る[ここ](https://docs.fileformat.com/compression/xz/) |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | AZ ファイルは、UNIX 圧縮データ ファイルに属するファイルのカテゴリです。圧縮された Unix ファイルは、最も一般的で広く使用されている Z ファイルの拡張子タイプです。 このファイル形式の詳細[ここ](https://docs.fileformat.com/compression/z/) |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | .zip 拡張子を持つファイルは、1 つ以上のファイルまたはディレクトリを保持できるアーカイブです。 ZIP ファイルのサイズを小さくするために、アーカイブに含まれるファイルに圧縮を適用できます。 このファイル形式の詳細[ここ](https://docs.fileformat.com/compression/zip/) |

### 関連項目

* class [FileType](../filetype)
* 名前空間 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 組み立て [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
