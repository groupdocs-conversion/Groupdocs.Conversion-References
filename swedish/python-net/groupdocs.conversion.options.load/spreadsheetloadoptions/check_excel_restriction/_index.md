---
title: "check_excel_restriction egenskap"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Egenskapen avgör om Excel-filrestriktioner kontrolleras när cellrelaterade objekt modifieras."
type: docs
url: /sv/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/
is_root: false
weight: 2030
---


## check_excel_restriction property

Egenskapen avgör om Excel-filrestriktioner kontrolleras när cellrelaterade objekt modifieras.

Om true, kommer ett försök att mata in en sträng längre än 32 K att utlösa ett undantag. Om false accepteras inmatningssträngen, vilket möjliggör att hela värdet kan skrivas ut till andra format som CSV. Däremot kan sparande av arbetsboken tillbaka till Excel-format med sådana ogiltiga värden orsaka oväntade fel.

### Definition:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

### Se även
* class [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)
