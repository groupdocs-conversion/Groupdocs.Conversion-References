---
title: "طريقة get_document_info"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يسترجع معلومات المستند المصدر، بما في ذلك عدد الصفحات وغيرها من الخصائص الخاصة بنوع الملف."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/get_document_info/
is_root: false
weight: 1070
---


## get_document_info

يسترجع معلومات المستند المصدر، بما في ذلك عدد الصفحات وغيرها من الخصائص الخاصة بنوع الملف.

```python
def get_document_info(self):
    ...
```

**Returns:** DocumentInfo: An object containing details such as format, pages count, creation date, size, and other type‑specific attributes.

### مثال

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### انظر أيضًا
* class [`IConversionSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsourcedocumentloaded/)
