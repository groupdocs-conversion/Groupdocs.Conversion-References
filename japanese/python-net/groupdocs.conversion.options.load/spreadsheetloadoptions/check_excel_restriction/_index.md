---
title: "check_excel_restriction プロパティ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "このプロパティは、セル関連オブジェクトを変更する際に Excel ファイルの制限がチェックされるかどうかを決定します。"
type: docs
url: /ja/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/
is_root: false
weight: 2030
---


## check_excel_restriction property

このプロパティは、セル関連オブジェクトを変更する際に Excel ファイルの制限がチェックされるかどうかを決定します。

true の場合、32 K を超える文字列の入力を試みると例外がスローされます。false の場合、入力文字列が受け入れられ、CSV などの他の形式へ完全な値を出力できます。ただし、そのような無効な値を含む状態でブックを Excel 形式に保存すると、予期しないエラーが発生する可能性があります。

### Definition:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

### 関連項目
* class [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)
