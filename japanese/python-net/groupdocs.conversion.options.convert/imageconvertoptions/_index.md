---
title: "ImageConvertOptions クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ドキュメントを画像ファイルタイプに変換するオプションを表します。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.convert/imageconvertoptions/
is_root: false
weight: 230
---


## ImageConvertOptions class

ドキュメントを画像ファイルタイプに変換するオプションを表します。

ImageConvertOptions 型は次のメンバーを公開します:

### コンストラクター
| コンストラクター | 説明 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/__init__/) | 新しい ImageConvertOptions インスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [background_color](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/background_color/) | ソース形式でサポートされている場合に使用する背景色。 |
| [brightness](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/brightness/) | 画像の明るさ調整。 |
| [cap_resolution_to_page_content](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) | このプロパティは、ページごとの PDF レンダリング解像度をページのネイティブラスタ解像度に制限し、埋め込まれた画像より高い DPI でのレンダリングを防ぎ、最終出力ではページをネイティブ（小さい）ピクセルサイズと DPI で出力します。 |
| [contrast](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/contrast/) | 画像に適用されるコントラスト調整。 |
| [crop_area](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/crop_area/) | 変換後のラスタ画像のクロップ領域。 |
| [flip_mode](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/flip_mode/) | 画像のフリップモード。 |
| [format](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/format/) | 入力ドキュメントを変換する目的のファイルタイプ。 |
| [gamma](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/gamma/) | 画像のガンマ調整。 |
| [grayscale](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/grayscale/) | 画像をグレースケールに変換するかどうかを示すオプション。 |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/height/) | 変換後の希望画像の高さです。 |
| [horizontal_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/horizontal_resolution/) | 変換後の希望画像の水平解像度です；デフォルトは入力ファイルの解像度または96 dpiです。 |
| [jpeg_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/jpeg_options/) | JPEG 固有の変換オプションです。 |
| [min_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/min_resolution/) | `[ImageConvertOptions.CapResolutionToPageContent]`(/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/cap_resolution_to_page_content/) が有効なときに、上限が設定されたレンダー DPI に適用される軸ごとの下限です。 |
| [page_number](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/page_number/) | 変換を開始するページ番号。 |
| [pages](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages/) | 変換するページインデックスのリスト。特定のページを変換する場合に指定します。 |
| [pages_count](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/pages_count/) | `PageNumber` から開始する変換ページ数。 |
| [psd_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/psd_options/) | PSD 固有の変換オプションです。 |
| [rotate_angle](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/rotate_angle/) | 画像の回転角度です。 |
| [tiff_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/tiff_options/) | Tiff 固有の変換オプションです。 |
| [use_pdf](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/use_pdf/) | UsePdf プロパティです。 |
| [vertical_resolution](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/vertical_resolution/) | 変換後の希望画像の垂直解像度です。デフォルトの解像度は入力ファイルの解像度または96 dpiです。 |
| [watermark](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/watermark/) | 透かし固有のオプション。 |
| [webp_options](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/webp_options/) | WebP 固有の変換オプションです。 |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/imageconvertoptions/width/) | 変換後の希望画像の幅です。 |

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

with Converter("slides.pptx") as converter:
    options = ImageConvertOptions()
    options.format = ImageFileType.PNG
    options.page_number = 1
    options.pages_count = 1
    converter.convert("slide-1.png", options)
```

### Guides
`ImageConvertOptions` を使用するタスクガイド:

* [Quick Start Guide](/conversion/python-net/guides/quick-start-guide/)
* [Convert Document To Multiple Page Files](/conversion/python-net/guides/convert-document-to-multiple-page-files/)

### 関連項目
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
