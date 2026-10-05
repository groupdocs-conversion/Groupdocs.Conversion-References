---
title: "طريقة get_document_info"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يسترجع معلومات المستند المصدر، بما في ذلك عدد الصفحات وغيرها من الخصائص الخاصة بنوع الملف."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/get_document_info/
is_root: false
weight: 1010
---


## get_document_info

يسترجع معلومات المستند المصدر، بما في ذلك عدد الصفحات وغيرها من الخصائص الخاصة بنوع الملف.

```python
def get_document_info(self):
    ...
```

### مثال

```python
from groupdocs.conversion import Converter

with Converter("document.pdf") as converter:
    info = converter.get_document_info()
    print(f"Pages: {info.pages_count}, Format: {info.format}")
```

### انظر أيضًا
* class [`IConversionGetDocumentInfo`](/conversion/python-net/groupdocs.conversion.fluent/iconversiongetdocumentinfo/)
