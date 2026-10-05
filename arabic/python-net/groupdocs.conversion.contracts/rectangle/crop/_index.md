---
title: "crop طريقة"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "ينشئ نسخة مقصوصة من المستطيل الحالي بإزالة الهوامش المحددة."
type: docs
url: /ar/python-net/groupdocs.conversion.contracts/rectangle/crop/
is_root: false
weight: 1010
---


## crop {#crop_left-crop_top-crop_right-crop_bottom}

ينشئ نسخة مقصوصة من المستطيل الحالي بإزالة الهوامش المحددة.

```python
def crop(self, crop_left, crop_top, crop_right, crop_bottom):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| crop_left | `int` | عدد البكسلات لإزالتها من الجانب الأيسر. |
| crop_top | `int` | عدد البكسلات لإزالتها من الجانب العلوي. |
| crop_right | `int` | عدد البكسلات لإزالتها من الجانب الأيمن. |
| crop_bottom | `int` | عدد البكسلات لإزالتها من الجانب السفلي. |

**Returns:** Rectangle: A new cropped rectangle.

### انظر أيضًا
* class [`Rectangle`](/conversion/python-net/groupdocs.conversion.contracts/rectangle/)
