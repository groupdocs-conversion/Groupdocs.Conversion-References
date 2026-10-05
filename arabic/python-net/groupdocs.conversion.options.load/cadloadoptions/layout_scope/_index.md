---
title: "خاصية layout_scope"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "نطاق التخطيط الذي يحدد أي مساحات الرسم يتم تحويلها."
type: docs
url: /ar/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/
is_root: false
weight: 2070
---


## layout_scope property

نطاق التخطيط الذي يحدد أي مساحات الرسم يتم تحويلها. القيمة الافتراضية هي [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/)، والتي لا تقيد التحويل. يتم تجاهلها عندما يتم توفير [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/)، لأن أسماء التخطيط الصريحة دائمًا تفوز. تُعامل القيمة `None` كـ [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/).

إذا كان النطاق لا يختار أيًا من الأوراق التي يقدمها الرسم، فإن التحويل يفشل مع `InvalidLoadOptionsException`، الذي يذكر النطاق والأوراق المتاحة بدلاً من عرض المساحات المستبعدة. الرسم الذي لا يقدم أي ورقة على الإطلاق لا يتأثر ولا يزال يتحول كوحدة واحدة. لا يتم احترام ذلك عند التحويل إلى PDF/UA-1، للسبب المذكور في [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/).

### Definition:
```python
@property
def layout_scope(self):
    ...
@layout_scope.setter
def layout_scope(self, value):
    ...
```

### انظر أيضًا
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
