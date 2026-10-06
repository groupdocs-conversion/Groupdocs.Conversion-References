---
title: "auto_detect_rtl_direction プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "autodetectrtldirection プロパティは、主に右から左へ書かれたテキストを含む段落やランが、変換前にバイディレクショナルフラグを修正すべきかどうかを決定します。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/auto_detect_rtl_direction/
is_root: false
weight: 2010
---


## auto_detect_rtl_direction property

auto_detect_rtl_direction プロパティは、主に右から左のテキストを含む段落やランの bidi フラグが変換前に修正されるかどうかを決定します。

True（デフォルト）に設定すると、このプロパティは Microsoft Word と LibreOffice が使用するヒューリスティックを適用し、Google Docs などのツールが `<w:bidi/>` を省略し、RTL スクリプトのみを含むランに `<w:rtl w:val=\"0\"/>` を付加した OOXML を生成する際のアラビア語/ヘブライ語文書のレンダリングを修正します。False に設定すると、ソースマークアップの厳密な OOXML 解釈を保持します。

### Definition:
```python
@property
def auto_detect_rtl_direction(self):
    ...
@auto_detect_rtl_direction.setter
def auto_detect_rtl_direction(self, value):
    ...
```

### 関連項目
* class [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)
