---
title: "خاصية check_excel_restriction"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "تحدد الخاصية ما إذا كانت قيود ملف Excel تُفحص عند تعديل الكائنات المتعلقة بالخلايا."
type: docs
url: /ar/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/check_excel_restriction/
is_root: false
weight: 2030
---


## check_excel_restriction property

تحدد الخاصية ما إذا كانت قيود ملف Excel تُفحص عند تعديل الكائنات المتعلقة بالخلايا.

إذا كانت true، فإن محاولة إدخال سلسلة أطول من 32 K ستؤدي إلى رفع استثناء. إذا كانت false، يتم قبول سلسلة الإدخال، مما يسمح بإخراج القيمة الكاملة إلى صيغ أخرى مثل CSV. ومع ذلك، قد يتسبب حفظ المصنف مرة أخرى بصيغة Excel مع مثل هذه القيم غير الصالحة في حدوث أخطاء غير متوقعة.

### Definition:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

### انظر أيضًا
* class [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions/)
