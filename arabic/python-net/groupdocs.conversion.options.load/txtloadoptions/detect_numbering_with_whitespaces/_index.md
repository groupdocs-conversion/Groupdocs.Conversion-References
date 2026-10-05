---
title: "خاصية detect_numbering_with_whitespaces"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "تحدد الخاصية كيفية التعرف على عناصر القوائم المرقمة عند تحويل مستند نص عادي."
type: docs
url: /ar/python-net/groupdocs.conversion.options.load/txtloadoptions/detect_numbering_with_whitespaces/
is_root: false
weight: 2020
---


## detect_numbering_with_whitespaces property

الخاصية تحدد كيفية التعرف على عناصر القوائم المرقمة عند تحويل مستند نص عادي. القيمة الافتراضية هي True.

إذا تم تعيين هذا الخيار إلى False، فإن خوارزمية التعرف على القوائم تكتشف فقرات القوائم عندما تنتهي أرقام القوائم إما بنقطة أو قوس يمين أو رموز نقطية (مثل "•", "*", "-" أو "o").

إذا تم تعيين هذا الخيار إلى True، فإن الفراغات تُستخدم أيضاً كفواصل لأرقام القوائم: خوارزمية التعرف على القوائم لتنسيق الترقيم العربي (مثال، 1., 1.1.2.) تستخدم كل من الفراغات والنقطة (".") كرموز.

### Definition:
```python
@property
def detect_numbering_with_whitespaces(self):
    ...
@detect_numbering_with_whitespaces.setter
def detect_numbering_with_whitespaces(self, value):
    ...
```

### انظر أيضًا
* class [`TxtLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/txtloadoptions/)
