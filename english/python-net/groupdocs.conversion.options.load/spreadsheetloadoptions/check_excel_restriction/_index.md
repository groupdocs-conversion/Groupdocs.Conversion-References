---
title: check_excel_restriction property
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/
is_root: false
weight: 2030
---


## check_excel_restriction property

The property indicates whether to check Excel file restrictions when modifying cell-related objects.

For example, Excel does not allow inputting a string value longer than 32 K. When you input a value longer than 32 K, if this property is true, an exception is raised. If the property is false, the input string is accepted as the cell's value, allowing you to later output the complete string for other formats such as CSV. However, if you set a value that is invalid for the Excel file format, you should not save the workbook as an Excel file later; otherwise unexpected errors may occur in the generated Excel file.

### Definition:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

### See Also
* class [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)
