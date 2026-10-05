---
title: "طريقة with_events"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "سجِّل معالجات أحداث دورة حياة التحويل على حقيبة ConversionEvents التي تستمر طوال عمر المحول وتُطلق في كل عملية تحويل."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionfrom/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

سجّل معالجات أحداث دورة حياة التحويل على حقيبة [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) التي تعيش طوال عمر المحول وتُطلق في كل عملية تحويل.

يمكن استدعاؤها قبل أو بعد [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/).
تتراكم الاستدعاءات المتعددة: تُمرَّر نفس الحقيبة الداخلية إلى كل إجراء `configure`، لذا تبقى المعالجات التي تم ضبطها في الاستدعاءات السابقة ما لم يتم استبدالها لاحقًا.

```python
def with_events(self, configure):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | الإجراء الذي يغيّر حقيبة الأحداث. |

**Returns:** This stage so that further entry-stage calls or `Load` may be chained.

### انظر أيضًا
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
