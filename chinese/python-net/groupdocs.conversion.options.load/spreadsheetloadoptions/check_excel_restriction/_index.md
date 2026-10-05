---
title: "check_excel_restriction 属性"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "该属性决定在修改单元格相关对象时是否检查 Excel 文件限制。"
type: docs
url: /zh/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/
is_root: false
weight: 2030
---


## check_excel_restriction property

该属性决定在修改单元格相关对象时是否检查 Excel 文件限制。

如果为 true，尝试输入超过 32 K 的字符串将引发异常。如果为 false，输入的字符串将被接受，允许将完整值输出到诸如 CSV 等其他格式。然而，将工作簿保存回 Excel 格式时，包含此类无效值可能会导致意外错误。

### Definition:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

### 另见
* class [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)
