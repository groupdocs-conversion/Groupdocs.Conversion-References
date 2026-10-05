---
title: "طريقة set_license"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "تطبيق ترخيص على العملية الحالية."
type: docs
url: /ar/python-net/groupdocs.conversion/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

تطبيق ترخيص على العملية الحالية.

```python
def set_license(self, license_source):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| license_source |  | إما مسار سلسلة إلى ملف ``.lic`` أو كائن شبيه بملف قابل للقراءة يُعيد بايتات الترخيص. تُكتب المدخلات الشبيهة بالملف إلى ملف مؤقت قبل تمريره إلى الجسر. |

| يُثير | الوصف |
| :- | :- |
| `TypeError` | إذا لم يكن ``license_source`` مسار سلسلة ولا كائن شبيه بملف قابل للقراءة. |

### انظر أيضًا
* class [`License`](/conversion/python-net/groupdocs.conversion/license/)
