---
title: "convert メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "変換チェーンを実行します。"
type: docs
url: /ja/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/convert/
is_root: false
weight: 1030
---


## convert

変換チェーンを実行します。

```python
def convert(self):
    ...
```

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document():
    # ソース ドキュメントを開く
    with Converter("./business-plan.docx") as converter:
        # PDF 出力の変換オプションを定義する
        pdf_options = PdfConvertOptions()
        # 変換を実行し、結果を保存する
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document()
```

### 関連項目
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
