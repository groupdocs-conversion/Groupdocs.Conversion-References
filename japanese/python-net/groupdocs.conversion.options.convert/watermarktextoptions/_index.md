---
title: "WatermarkTextOptions クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換されたドキュメントにテキスト透かしを設定するオプション。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.convert/watermarktextoptions/
is_root: false
weight: 590
---


## WatermarkTextOptions class

変換されたドキュメントにテキスト透かしを設定するオプション。

透かしの外観設定を表します。以下のプロパティを構成できます:

- `text`: The text to be used for the watermark.
- `font`: The font name used for the watermark text.
- `color`: The color of the watermark text.
- `top`: The top offset of the watermark.
- `left`: The left offset of the watermark.
- `width`: The width of the watermark.
- `height`: The height of the watermark.
- `background`: Whether the watermark is rendered in the background.

WatermarkTextOptions 型は次のメンバーを公開します:

### コンストラクター
| コンストラクター | 説明 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/__init__/#text) | 指定された透かしテキストで WatermarkTextOptions インスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [clone](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/clone/) | 現在のインスタンスをクローンします。( [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/) から継承 ) |
| [equals](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals/) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。(inherited from [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_object/) | (inherited from [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [equals_value_object](/conversion/python-net/groupdocs.conversion.contracts/valueobject/equals_value_object/) | (inherited from [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/) | デフォルトのハッシュ関数として機能します。(inherited from [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)) |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [color](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/color/) | テキスト透かしが適用された場合の透かしフォントカラーです。 |
| [text](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/text/) | 透かしテキストです。 |
| [watermark_font](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/watermark_font/) | テキスト透かしが適用されたときに使用される透かしフォントです。 |
| [auto_align](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/auto_align/) | 透かしは True に設定された場合、ページサイズに合わせて自動的にスケーリングされます。(inherited from [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [background](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/background/) | 透かしは背景としてスタンプされます。True の場合は下部に配置され、そうでない場合は上部に配置されます（デフォルトは False）。(inherited from [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [height](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/height/) | 透かしの高さ。(inherited from [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [left](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/left/) | 透かしの左位置。(inherited from [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [rotation_angle](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/rotation_angle/) | 透かしの回転角度。(inherited from [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [top](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/top/) | 透かしの上位置。(inherited from [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [transparency](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/transparency/) | 透かしの透明度。0 から 1 の値です。0 の場合は完全に表示され、1 の場合は見えません。(inherited from [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |
| [width](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/width/) | 透かしの幅。(inherited from [`WatermarkOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarkoptions/)) |

### 例

```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

with Converter("./professional-services.docx") as converter:
    watermark = WatermarkTextOptions("DRAFT")
    watermark.color = Color.from_argb(128, 211, 211, 211)  # lite gray
    watermark.top = 10
    watermark.left = 10
    watermark.width = 300
    watermark.height = 300
    watermark.background = True

    options = PdfConvertOptions()
    options.pages_count = 1
    options.watermark = watermark

    converter.convert("./professional-services.pdf", options)
```

### Guides
`WatermarkTextOptions` を使用するタスク ガイド:

* [Add a Watermark to Converted Document](/conversion/python-net/guides/add-watermark-to-converted-document/)

### 関連項目
* module [`groupdocs.conversion.options.convert`](/conversion/python-net/groupdocs.conversion.options.convert/)
