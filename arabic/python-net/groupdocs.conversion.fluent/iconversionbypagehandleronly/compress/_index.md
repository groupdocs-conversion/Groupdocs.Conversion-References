---
title: "طريقة الضغط"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يضغط نتائج التحويل؛ سجّل معالج تدفق مضغوط في مرحلة الإدخال عبر IConversionSettings.withevents (تعيين OnCompressionCompleted) بدلاً من استخدام السلسلة السائلة القديمة…"
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/compress/
is_root: false
weight: 1010
---


## compress {#options}

يضغط نتائج التحويل؛ سجّل معالج تدفق مضغوط في مرحلة الدخول عبر [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (تعيين `OnCompressionCompleted`) بدلاً من استخدام طريقة السلسلة السائلة القديمة.

```python
def compress(self, options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | `CompressionConvertOptions` | خيارات تحويل الضغط. |

**Returns:** Continuation that proceeds to `Convert`.

### انظر أيضًا
* class [`IConversionByPageHandlerOnly`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypagehandleronly/)
