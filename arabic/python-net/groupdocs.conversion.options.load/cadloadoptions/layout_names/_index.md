---
title: "خاصية layout_names"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "أسماء التخطيط التي سيتم تحويلها."
type: docs
url: /ar/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/
is_root: false
weight: 2060
---


## layout_names property

أسماء التخطيط التي سيتم تحويلها.

لا يُحترم عند التحويل إلى PDF/UA-1. ذلك الهدف يعرض الرسم كصفحة واحدة موسومة، والتي لا يمكنها حمل ورقة واحدة لكل تخطيط مختار، لذا يتم تحويل الرسم بالكامل بدلاً من ذلك ولا ينطبق شيء هنا عليه.

كل هدف آخر، بما في ذلك PDF، يلتزم بالاختيار. في تلك الأهداف، يتم مطابقة الأسماء بدقة مع التخطيطات التي يحملها الرسم، لذا فإن الاسم الذي يختلف فقط في حالة الأحرف يُعد اسماً مختلفاً. الاسم الذي لا يطابق شيئاً يُحذف ويكلف المتصل تلك الورقة فقط؛ القائمة التي لا يطابق فيها شيء تفشل التحويل مع `InvalidLoadOptionsException` الذي يذكر الأسماء التي لم تُطابق والتخطيطات التي يحملها الرسم، بدلاً من عرض الأوراق التي لم يطلبها المتصل. الرسم الذي لا يحمل أي تخطيطات على الإطلاق مستثنى: لا يوجد ما يطابق الاسم، لذا لا يُرفض شيء.

### Definition:
```python
@property
def layout_names(self):
    ...
@layout_names.setter
def layout_names(self, value):
    ...
```

### انظر أيضًا
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
