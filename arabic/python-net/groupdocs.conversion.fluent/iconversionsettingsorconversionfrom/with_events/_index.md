---
title: "طريقة with_events"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يسجّل معالجات أحداث دورة حياة التحويل على حقيبة ConversionEvents التي تستمر طوال عمر المحول وتُطلق في كل تشغيل تحويل."
type: docs
url: /ar/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

يسجل معالجات أحداث دورة حياة التحويل على حقيبة [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) التي تستمر طوال عمر المحول وتطلق في كل تشغيل تحويل.

إنه يقع في نفس مرحلة الدخول مثل [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/). تتراكم الاستدعاءات المتعددة: تُمرَّر نفس الحقيبة الداخلية إلى كل إجراء `configure`، لذا تبقى المعالجات التي تم تعيينها في الاستدعاءات السابقة ما لم يتم استبدالها بأخرى لاحقة.

```python
def with_events(self, configure):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | الإجراء الذي يغيّر حقيبة الأحداث. |

**Returns:** The source-selection stage so that `Load` may be chained.

### انظر أيضًا
* class [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/)
