---
title: "طريقة convert_by_page_to"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يحفظ الصفحة المحولة كتيار."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/convert_by_page_to/
is_root: false
weight: 1010
---


## convert_by_page_to {#converted_stream_provider}

يحفظ الصفحة المحولة كتيار.

```python
def convert_by_page_to(self, converted_stream_provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| converted_stream_provider | `Func[SavePageContext, io.RawIOBase]` | موفر تدفق صفحة المستند المحول. |

**Returns:** Page options or handler setup interface to continue conversion building.

### انظر أيضًا
* class [`IConversionLoadOptionsOrSourceDocumentLoaded`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded/)
