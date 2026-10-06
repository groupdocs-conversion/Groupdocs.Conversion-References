---
title: "CompressionFileType クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "圧縮形式を定義します。"
type: docs
url: /ja/python-net/groupdocs.conversion.filetypes/compressionfiletype/
is_root: false
weight: 30
---


## CompressionFileType class

圧縮形式を定義します。

- [`CompressionFileType.zip`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/zip/)
- [`CompressionFileType.rar`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/rar/)
- [`CompressionFileType.seven_z`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/seven_z/)
- [`CompressionFileType.tar`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/tar/)
- [`CompressionFileType.gz`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/gz/)
- [`CompressionFileType.gzip`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/gzip/)
- [`CompressionFileType.bz2`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/bz2/)
- [`CompressionFileType.lz`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/lz/)
- [`CompressionFileType.z`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/z/)
- [`CompressionFileType.xz`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/xz/)
- [`CompressionFileType.cpio`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/cpio/)
- [`CompressionFileType.cab`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/cab/)
- [`CompressionFileType.lzma`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/lzma/)
- [`CompressionFileType.zst`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/zst/)
- [`CompressionFileType.uue`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/uue/)
- [`CompressionFileType.lha`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/lha/)
- [`CompressionFileType.lz4`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/lz4/)
- [`CompressionFileType.xar`](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/xar/)

圧縮形式の詳細については https://docs.fileformat.com/compression/ をご覧ください。

CompressionFileType 型は以下のメンバーを公開します：

### メソッド
| メソッド | 説明 |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | 現在のオブジェクトを他と比較します。（[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) から継承） |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | （[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) から継承） |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/) によって定義された等価比較を実装します。（[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/) から継承） |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | （[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/) から継承） |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | （[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) から継承） |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | （[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) から継承） |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | 提供されたファイル拡張子の FileType を取得します。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | 指定された file_name の FileType を返します。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | 提供されたドキュメントストリームの FileType を返します。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | （[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) から継承） |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | （[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/) から継承） |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | デフォルトのハッシュ関数を提供します。（[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/) から継承） |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | ファイルタイプの文字列表現です。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [is_multi_file_archive](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/is_multi_file_archive/) | この形式は単一のアーカイブ内で複数のファイル/フォルダーをサポートします。 |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | ファイルタイプの説明です。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | ファイル拡張子です。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | ファイルファミリーです。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | ファイル形式です。(継承元 [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### フィールド
| フィールド | 説明 |
| :- | :- |
| [ZIP](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/zip/) | .zip 拡張子のファイルは、1つ以上のファイルやディレクトリを格納できるアーカイブです。アーカイブは含まれるファイルに圧縮を適用して ZIP ファイルサイズを削減できます。このファイル形式の詳細はここで確認してください。 |
| [RAR](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/rar/) | .rar 拡張子のファイルは、圧縮または通常形式で情報を保存するために作成されたアーカイブファイルです。RAR は Roshal ARchive ファイル形式の略です。このファイル形式の詳細はここで確認してください。 |
| [SEVEN_Z](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/seven_z/) | 7z は高い圧縮率でファイルやフォルダーを圧縮するアーカイブ形式です。オープンソースのアーキテクチャに基づいており、任意の圧縮および暗号化アルゴリズムを使用できます。このファイル形式の詳細はここで確認してください。 |
| [TAR](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/tar/) | .tar 拡張子のファイルは、1つ以上のファイルを収集するために Unix 系ユーティリティで作成されたアーカイブです。複数のファイルは非圧縮形式で保存され、ファイルやフォルダーをアーカイブに追加することがサポートされています。このファイル形式の詳細はここで確認してください。 |
| [GZ](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/gz/) | GZ ファイルは、標準の gzip（GNU zip）圧縮アルゴリズムを使用して作成された圧縮アーカイブです。複数の圧縮ファイル、ディレクトリ、ファイルスタブを含むことがあります。このファイル形式の詳細はここで確認してください。 |
| [GZIP](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/gzip/) | Gzip ファイルは、標準の gzip（GNU zip）圧縮アルゴリズムを使用して作成された圧縮アーカイブです。複数の圧縮ファイル、ディレクトリ、ファイルスタブを含むことがあります。このファイル形式の詳細はここで確認してください。 |
| [BZ2](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/bz2/) | BZ2 は BZIP2 オープンソース圧縮方式で生成された圧縮ファイルで、主に UNIX または Linux システムで使用されます。単一ファイルの圧縮に使用され、複数ファイルのアーカイブには適していません。このファイル形式の詳細はここで確認してください。 |
| [LZ](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/lz/) | .lz 拡張子のファイルは、圧縮用のフリーコマンドラインツール Lzip で作成された圧縮アーカイブファイルです。連結圧縮をサポートします。LZ ファイルはメディアタイプ application/lzip を持ち、BZ2 より高い圧縮率をサポートしています。このファイル形式の詳細はここで確認してください。 |
| [Z](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/z/) | Z ファイルは UNIX 圧縮データファイルに属するファイルのカテゴリです。圧縮された Unix ファイルは Z ファイルの中で最も一般的で広く使用されている拡張子です。このファイル形式の詳細はここで確認してください。 |
| [XZ](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/xz/) | XZ は LZMA2 圧縮アルゴリズムを利用した圧縮ファイル形式です。一般的な gzip および bzip2 形式の代替として設計され、これらの古い標準に比べて多くの利点があります。このファイル形式の詳細はここで確認してください。 |
| [CPIO](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/cpio/) | Cpio は汎用のファイルアーカイバユーティリティおよびそれに関連するファイル形式です。主に Unix 系のコンピュータ OS にインストールされています。 |
| [CAB](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/cab/) | .cab 拡張子のファイルは、システムファイルのカテゴリに属する Windows キャビネットファイルです。LZX、Quantum、ZIP などの圧縮データアルゴリズムをサポートする Microsoft Windows のバージョンで、アーカイブ形式で保存されます。このファイル形式の詳細はここで確認してください。 |
| [LZMA](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/lzma/) | .lzma 拡張子のファイルは、LZMA（Lempel-Ziv-Markov chain Algorithm）圧縮方式で作成された圧縮アーカイブファイルです。主に Unix OS で見られ、ZIP など他の圧縮アルゴリズムと同様にファイルサイズの最小化に使用されます。このファイル形式の詳細はここで確認してください。 |
| [ZST](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/zst/) | ZST ファイルは Zstandard（zstd）圧縮アルゴリズムで生成された圧縮ファイルです。アルゴリズムによるロスレス圧縮で作成されたファイルです。このファイル形式の詳細はここで確認してください。 |
| [ISO](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/iso/) | .iso 拡張子のファイルは、CD や DVD などの光学ディスク上の全データ内容を表す、非圧縮のアーカイブディスクイメージファイルです。ISO-9660 標準に基づき、ISO イメージファイル形式はディスクデータとそれに格納されたファイルシステム情報を含みます。このファイル形式の詳細はここで確認してください。 |
| [UUE](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/uue/) | uuencode アーカイブは、Unix-to-Unix エンコーディング方式（uuencode）でエンコードされたファイルまたはファイルの集合です。このエンコーディング手法はバイナリデータをテキスト形式に変換し、メールなどテキストのみ対応のチャネルでファイルを送信しやすくします。 |
| [LHA](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/lha/) | .lzh と .lha 拡張子を持つファイルは、通常アーカイブ圧縮ファイル形式に該当します。このファイル形式は ZIP、RAR などの他の圧縮ファイル形式と同様です。これらのファイル形式の主な目的は、サイズを縮小して容易に送信できるようにし、圧縮された形でまとめて保持することです。 |
| [LZ4](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/lz4/) | .lz4 拡張子のファイルは、LZ4 圧縮をサポートするアプリケーション/ユーティリティで作成された圧縮アーカイブファイルです。LZ4 アルゴリズムは速度と圧縮率のトレードオフに重点を置いています。圧縮された LZ4 アーカイブは LZ4 コマンドラインユーティリティで作成でき、同じユーティリティで解凍できます。こちらでこのファイル形式の詳細を確認してください。 |
| [XAR](/conversion/python-net/groupdocs.conversion.filetypes/compressionfiletype/xar/) | .xar 拡張子のファイルは eXtensible ARchive（拡張可能アーカイブ）で、圧縮された XML として保存された目次を中心に構成された形式です。macOS のインストーラーパッケージ配布に使用され、各エントリは個別に圧縮されたまま保持されます。こちらでこのファイル形式の詳細を確認してください。 |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 不明なファイルタイプ（[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/) から継承） |

### 関連項目
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
