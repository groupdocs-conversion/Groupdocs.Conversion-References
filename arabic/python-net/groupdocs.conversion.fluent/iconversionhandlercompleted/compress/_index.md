---
title: "طريقة الضغط"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يضغط نتائج التحويل ويعيد استمرارية تستمر إلى Convert."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/compress/
is_root: false
weight: 1010
---


## compress {#options}

يضغط نتائج التحويل ويعيد متابعة تتقدم إلى `Convert`.

سجّل معالج تدفق مضغوط في مرحلة الدخول عبر [`IConversionSettings.with_events`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_events/) (تعيين `OnCompressionCompleted`) بدلاً من استخدام طريقة السلسلة المتقاربة القديمة على الواجهة المرجعة.

```python
def compress(self, options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | `CompressionConvertOptions` | خيارات تحويل الضغط. |

**Returns:** Continuation that proceeds to `Convert`.

### انظر أيضًا
* class [`IConversionHandlerCompleted`](/conversion/python-net/groupdocs.conversion.fluent/iconversionhandlercompleted/)
