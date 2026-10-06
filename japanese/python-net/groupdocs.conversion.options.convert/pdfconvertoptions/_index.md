---
title: "PdfConvertOptions クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "PDF ファイルタイプへの変換オプションです。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/
is_root: false
weight: 340
---


## PdfConvertOptions class

PDF ファイルタイプへの変換オプションです。

PdfConvertOptions 型は次のメンバーを公開します:

### コンストラクター
| コンストラクター | 説明 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/__init__/) | 新しい [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) インスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [dpi](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/dpi/) | 変換後の希望ページ DPI。デフォルトの解像度は 96 dpiです。 |
| [embed_full_fonts](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/embed_full_fonts/) | このプロパティは、サブセットではなくフォント全体のファイルを PDF に埋め込むかどうかを決定します。 |
| [fallback_page_size](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/fallback_page_size/) | フォールバックページサイズです。 |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/format/) | 入力ドキュメントを変換する目的のファイルタイプ。 |
| [margin_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/margin_settings/) | PDF 変換時に適用される余白設定です。 |
| [orientation_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/orientation_settings/) | 向き設定です。 |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/page_number/) | 変換を開始するページ番号。 |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages/) | 変換対象のページインデックスの一覧です。特定のページを変換する場合に指定します。 |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pages_count/) | `page_number` から開始する変換ページ数です。 |
| [password](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/password/) | 変換されたドキュメントを保護するために使用されるパスワード。 |
| [pdf_options](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/pdf_options/) | PDF 固有の変換オプションです。 |
| [resize_mode](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/resize_mode/) | リサイズモードは、ページサイズが変更されたときにコンテンツをどのように拡大縮小するかを指定します。デフォルトは AlignTopLeft（拡大縮小なし）です。 |
| [rotate](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/rotate/) | ページの回転です。 |
| [size_settings](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/size_settings/) | PDF 変換時に使用されるページサイズ設定です。 |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/watermark/) | 透かし固有のオプション。 |

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Guides
`PdfConvertOptions` を使用するタスク ガイド:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert a Document to Another Format](/conversion/python-net/guides/convert-document-to-another-format/)
* [Convert Files Within Document Containers](/conversion/python-net/guides/convert-files-within-document-containers/)
* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)
* [Load File From Local Disk](/conversion/python-net/guides/load-file-from-local-disk/)
* [Load Password-Protected File](/conversion/python-net/guides/load-password-protected-file/)

### 関連項目
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
