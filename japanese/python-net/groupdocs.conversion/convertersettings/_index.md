---
title: "ConverterSettings クラス"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "Converter の動作をカスタマイズする設定を定義します。"
type: docs
url: /ja/python-net/groupdocs.conversion/convertersettings/
is_root: false
weight: 90
---


## ConverterSettings class

Converter の動作をカスタマイズする設定を定義します。

ConverterSettings 型は次のメンバーを公開します:

### コンストラクター
| コンストラクター | 説明 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/convertersettings/__init__/) | デフォルト値で ConverterSettings の新しいインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [cache](/conversion/python-net/groupdocs.conversion/convertersettings/cache/) | 変換結果を保存するために使用されるキャッシュ実装です。 |
| [font_directories](/conversion/python-net/groupdocs.conversion/convertersettings/font_directories/) | カスタムフォントディレクトリのパスです。 |
| [listener](/conversion/python-net/groupdocs.conversion/convertersettings/listener/) | 変換ステータスと進行状況を監視するために使用されるコンバータリスナー実装で、Started、Progress、Completed コールバックは、[`ConversionEvents.on_conversion_started`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/)、[`ConversionEvents.on_conversion_progress`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/)、[`ConversionEvents.on_conversion_completed`](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) に転送され、[`Converter`](/conversion/python-net/groupdocs.conversion/converter/) の構築時に使用されます。 |
| [logger](/conversion/python-net/groupdocs.conversion/convertersettings/logger/) | 変換プロセスのロギングに使用されるロガー実装です。 |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/convertersettings/on_compression_completed/) | 圧縮完了時のイベントハンドラです。 |
| [on_conversion_by_page_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_by_page_failed/) | ページ単位の変換が失敗したときに呼び出されるイベントハンドラです。 |
| [on_conversion_failed](/conversion/python-net/groupdocs.conversion/convertersettings/on_conversion_failed/) | 変換が失敗したときに呼び出されるイベントハンドラです。 |
| [scan_font_directories_recursively](/conversion/python-net/groupdocs.conversion/convertersettings/scan_font_directories_recursively/) | True に設定されている場合、コンバータはフォントディレクトリを再帰的にスキャンします。 |
| [temp_folder](/conversion/python-net/groupdocs.conversion/convertersettings/temp_folder/) | 変換に使用される一時フォルダーです。 |

### 例

```python
from groupdocs.conversion import Converter, ConverterSettings
from groupdocs.conversion.logging import ConsoleLogger
from groupdocs.conversion.options.convert import PdfConvertOptions

settings = ConverterSettings()
settings.logger = ConsoleLogger()

with Converter("input.docx", settings) as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### 関連項目
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
