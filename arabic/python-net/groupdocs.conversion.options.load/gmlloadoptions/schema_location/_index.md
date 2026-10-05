---
title: "خاصية schema_location"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "الموقع المخطط (schemalocation) هو قائمة مفصولة بمسافات من أزواج URI، حيث يكون الـ URI الأول في كل زوج هو URI للمساحة الاسمية والـ URI الثاني هو المسار إلى مخطط XML لتلك المساحة الاسمية."
type: docs
url: /ar/python-net/groupdocs.conversion.options.load/gmlloadoptions/schema_location/
is_root: false
weight: 2040
---


## schema_location property

المتغيّر schema_location هو قائمة مفصولة بمسافات من أزواج URI، حيث يكون الـ URI الأول في كل زوج هو URI للمساحة الاسمية والـ URI الثاني هو مسار مخطط XML لتلك المساحة الاسمية.

إذا تم تعيينه إلى None، سيحاول Conversion قراءة سمة schemaLocation من العنصر الجذر للمستند. القيمة الافتراضية هي None.

### Definition:
```python
@property
def schema_location(self):
    ...
@schema_location.setter
def schema_location(self, value):
    ...
```

### انظر أيضًا
* class [`GmlLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/gmlloadoptions/)
