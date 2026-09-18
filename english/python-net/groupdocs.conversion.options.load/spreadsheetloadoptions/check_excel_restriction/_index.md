---
title: check_excel_restriction property
second_title: GroupDocs.Conversion for Python via .NET API References
description: "The property determines whether Excel file restrictions are checked when modifying cell-related objects."
type: docs
url: /python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/
is_root: false
weight: 2030
---


## check_excel_restriction property

The property determines whether Excel file restrictions are checked when modifying cell-related objects.

If true, attempting to input a string longer than 32 K will raise an exception. If false, the input string is accepted, allowing the full value to be output to other formats such as CSV. However, saving the workbook back to Excel format with such invalid values may cause unexpected errors.

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
