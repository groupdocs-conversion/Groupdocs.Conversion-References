---
title: "CompressionFileType"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "圧縮形式を定義します。以下のファイルタイプが含まれます Zip./compressionfiletype/zip. Rar./compressionfiletype/rar. SevenZ./compressionfiletype/sevenz. Tar./compressionfiletype/tar. Gz./compressionfiletype/gz. Gzip./compressionfiletype/gzip. Bz2./compressionfiletype/bz2. Lz./compressionfiletype/lz. Z./compressionfiletype/z. Xz./compressionfiletype/xz. Xz./compressionfiletype/xz. Cpio./compressionfiletype/cpio. Cab./compressionfiletype/cab. Lzma./compressionfiletype/lzma. Zst./compressionfiletype/zst. Uue./compressionfiletype/uue. Lha./compressionfiletype/lha. Lz4./compressionfiletype/lz4. Xar./compressionfiletype/xar. Wim./compressionfiletype/wim. Aar./compressionfiletype/aar. Alz./compressionfiletype/alz. 圧縮形式の詳細はここをご覧くださいhttps//docs.fileformat.com/compression/。"
type: docs
weight: 1080
url: /ja/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

圧縮形式を定義します。以下のファイルタイプが含まれます: [`Zip`](./zip). [`Rar`](./rar). [`SevenZ`](./sevenz). [`Tar`](./tar). [`Gz`](./gz). [`Gzip`](./gzip). [`Bz2`](./bz2). [`Lz`](./lz). [`Z`](./z). [`Xz`](./xz). [`Xz`](./xz). [`Cpio`](./cpio). [`Cab`](./cab). [`Lzma`](./lzma). [`Zst`](./zst). [`U`](./uue). [`Lha`](./lha). [`Lz4`](./lz4). [`Xar`](./xar). [`Wim`](./wim). [`Aar`](./aar). [`Alz`](./alz). 圧縮形式の詳細は[こちら](https://docs.fileformat.com/compression/)をご覧ください。

```csharp
public sealed class CompressionFileType : FileType
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | ファイルタイプの説明 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | ファイル拡張子 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | ファイルファミリー |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | ファイル形式 |
| [IsMultiFileArchive](../../groupdocs.conversion.filetypes/compressionfiletype/ismultifilearchive) { get; } | 単一のアーカイブ内で複数のファイル/フォルダーをサポートするかどうかを定義します。 |

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
| static readonly [Aar](../../groupdocs.conversion.filetypes/compressionfiletype/aar) | .aar 拡張子のファイルは Apple Archive で、Apple が macOS に同梱しているファイルやフォルダーをグループ化するコンテナです。各エントリは個別に圧縮され、主に LZFSE が使用されます。 |
| static readonly [Alz](../../groupdocs.conversion.filetypes/compressionfiletype/alz) | .alz 拡張子のファイルは ALZip アーカイブで、ESTsoft が提供し韓国で広く使用されている形式です。エントリはパスワードで個別に暗号化できる場合があります。このファイル形式の詳細は[here](https://docs.fileformat.com/compression/alz/)で確認してください。 |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2 は BZIP2 オープンソース圧縮方式で生成された圧縮ファイルで、主に UNIX または Linux システムで使用されます。単一ファイルの圧縮に使用され、複数ファイルのアーカイブには適していません。このファイル形式の詳細は[here](https://docs.fileformat.com/compression/bz2/)で確認してください。 |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | .cab 拡張子のファイルは Windows キャビネットファイルで、システムファイルのカテゴリに属します。Microsoft Windows の圧縮データアルゴリズム（LZX、Quantum、ZIP など）をサポートするバージョンで、アーカイブ形式として保存されます。このファイル形式の詳細は[here](https://docs.fileformat.com/system/cab/)で確認してください。 |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio は一般的なファイルアーカイバユーティリティおよびそれに関連するファイル形式です。主に Unix 系のコンピュータオペレーティングシステムにインストールされています。 |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | GZ ファイルは標準の gzip（GNU zip）圧縮アルゴリズムを使用して作成された圧縮アーカイブです。複数の圧縮ファイル、ディレクトリ、ファイルスタブを含むことができます。このファイル形式の詳細は[here](https://docs.fileformat.com/compression/gz/)で確認してください。 |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Gzip ファイルは標準の gzip（GNU zip）圧縮アルゴリズムを使用して作成された圧縮アーカイブです。複数の圧縮ファイル、ディレクトリ、ファイルスタブを含むことができます。このファイル形式の詳細は[here](https://docs.fileformat.com/compression/gz/)で確認してください。 |
| static readonly [Iso](../../groupdocs.conversion.filetypes/compressionfiletype/iso) | .iso 拡張子のファイルは、CD や DVD などの光学ディスク上の全データ内容を表す非圧縮アーカイブディスクイメージファイルです。ISO-9660 標準に基づき、ディスクデータとファイルシステム情報を含みます。このファイル形式の詳細は[here](https://docs.fileformat.com/compression/iso/)で確認してください。 |
| static readonly [Lha](../../groupdocs.conversion.filetypes/compressionfiletype/lha) | .lzh および .lha 拡張子のファイルは、通常アーカイブ圧縮形式に関連し、ZIP や RAR などと同様の圧縮形式です。これらの形式の主な目的は、サイズを縮小して容易に送信できるようにし、圧縮された形でまとめて保持することです。 |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | .lz 拡張子のファイルは Lzip で作成された圧縮アーカイブで、フリーのコマンドライン圧縮ツールです。連結圧縮をサポートし、メディアタイプは application/lzip で、BZ2 より高い圧縮率を提供します。このファイル形式の詳細は[here](https://docs.fileformat.com/compression/bz2/)で確認してください。 |
| static readonly [Lz4](../../groupdocs.conversion.filetypes/compressionfiletype/lz4) | .lz4 拡張子のファイルは LZ4 圧縮をサポートするアプリケーション/ユーティリティで作成された圧縮アーカイブです。LZ4 アルゴリズムは速度と圧縮率のトレードオフに焦点を当てています。LZ4 コマンドラインユーティリティで圧縮および解凍が可能です。このファイル形式の詳細は[here](https://docs.fileformat.com/compression/lz4/)で確認してください。 |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | .lzma 拡張子のファイルは LZMA（Lempel-Ziv-Markov chain Algorithm）圧縮方式で作成された圧縮アーカイブです。主に Unix 系 OS で使用され、ZIP など他の圧縮アルゴリズムと同様にファイルサイズの最小化に利用されます。このファイル形式の詳細は[here](https://docs.fileformat.com/compression/lzma/)で確認してください。 |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | .rar 拡張子のファイルは、圧縮または非圧縮の形で情報を保存するために作成されたアーカイブファイルです。RAR は Roshal ARchive の略です。このファイル形式の詳細は[here](https://docs.fileformat.com/compression/rar/)で確認してください。 |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z は高い圧縮率でファイルやフォルダーを圧縮するためのアーカイブ形式で、オープンソースアーキテクチャに基づき、任意の圧縮および暗号化アルゴリズムの使用が可能です。このファイル形式の詳細は[here](https://docs.fileformat.com/compression/7z/)で確認してください。 |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | .tar 拡張子のファイルは Unix 系ユーティリティで作成されたアーカイブで、1 つまたは複数のファイルをまとめます。複数のファイルは非圧縮形式で保存され、ファイルやフォルダーをアーカイブに追加することがサポートされています。このファイル形式の詳細は[here](https://docs.fileformat.com/compression/tar/)で確認してください。 |
| static readonly [Uue](../../groupdocs.conversion.filetypes/compressionfiletype/uue) | uuencode アーカイブは、Unix-to-Unix エンコーディング方式（uuencode）でエンコードされたファイルまたはファイル集合です。このエンコーディングはバイナリデータをテキスト形式に変換し、メールなどテキストのみをサポートするチャネルでの送信を容易にします。 |
| static readonly [Wim](../../groupdocs.conversion.filetypes/compressionfiletype/wim) | .wim 拡張子のファイルは Windows Imaging Format アーカイブで、Microsoft が Windows の展開に使用するファイルベースのディスクイメージです。単一のアーカイブは 1 つ以上のイメージを保持し、各ファイルはイメージ数に関係なく一度だけ保存されます。このファイル形式の詳細は[here](https://docs.fileformat.com/disc-and-media/wim/)で確認してください。 |
| static readonly [Xar](../../groupdocs.conversion.filetypes/compressionfiletype/xar) | .xar 拡張子のファイルは eXtensible ARchive で、圧縮 XML として保存された目次テーブルを中心に構成された形式です。macOS のインストーラーパッケージ配布に使用され、各エントリは個別に圧縮されます。このファイル形式の詳細は[here](https://docs.fileformat.com/compression/xar/)で確認してください。 |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ は LZMA2 圧縮アルゴリズムを利用した圧縮ファイル形式で、一般的な gzip や bzip2 の代替として設計され、これらの古い標準に比べて多数の利点を提供します。このファイル形式の詳細は[here](https://docs.fileformat.com/compression/xz/)で確認してください。 |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | Z ファイルは UNIX 圧縮データファイルに属するカテゴリで、圧縮された Unix ファイルは Z ファイルの中で最も一般的かつ広く使用されている拡張子です。このファイル形式の詳細は[here](https://docs.fileformat.com/compression/z/)で確認してください。 |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | .zip 拡張子のファイルは 1 つまたは複数のファイルやディレクトリを保持できるアーカイブで、含まれるファイルに圧縮を適用して ZIP ファイルサイズを削減できます。このファイル形式の詳細は[here](https://docs.fileformat.com/compression/zip/)で確認してください。 |
| static readonly [Zst](../../groupdocs.conversion.filetypes/compressionfiletype/zst) | ZST ファイルは Zstandard (zstd) 圧縮アルゴリズムで生成される圧縮ファイルです。アルゴリズムによるロスレス圧縮で作成された圧縮ファイルです。このファイル形式の詳細は[here](https://docs.fileformat.com/compression/zst/)でご覧ください。 |

### 関連項目

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
