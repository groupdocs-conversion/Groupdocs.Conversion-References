---
title: "طريقة get_document_info"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يسترجع معلومات المستند المصدر، بما في ذلك عدد الصفحات والخصائص الأخرى الخاصة بنوع الملف."
type: docs
url: /ar/python-net/groupdocs.conversion/converter/get_document_info/
is_root: false
weight: 1080
---


## get_document_info

يسترجع معلومات المستند المصدر، بما في ذلك عدد الصفحات والخصائص الأخرى الخاصة بنوع الملف.

تعرف على المزيد حول المستند المحوَّل – نوع الملف، عدد الصفحات، تاريخ الإنشاء والعديد من الخصائص الخاصة بالتنسيق:
- How to get document info (https://docs.groupdocs.com/display/conversionnet/Get+document+info)

```python
def get_document_info(self):
    ...
```

**Returns:** Document information as `IDocumentInfo`.

### مثال

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### انظر أيضًا
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
