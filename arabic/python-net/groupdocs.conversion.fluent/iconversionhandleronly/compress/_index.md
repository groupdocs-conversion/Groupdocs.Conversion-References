---
title: "طريقة الضغط"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يضغط نتائج التحويل."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionhandleronly/compress/
is_root: false
weight: 1010
---


## compress {#options}

يضغط نتائج التحويل.

سجِّل معالج تدفق مضغوط في مرحلة الدخول عبر [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (تعيين `OnCompressionCompleted`) بدلاً من عبر طريقة السلسلة السائلة القديمة على الواجهة المرتجعة.

```python
def compress(self, options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | `CompressionConvertOptions` | خيارات تحويل الضغط |

**Returns:** Continuation that proceeds to `Convert`.

### انظر أيضًا
* class [`IConversionHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandleronly/)
