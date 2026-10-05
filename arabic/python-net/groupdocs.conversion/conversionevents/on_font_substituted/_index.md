---
title: "خاصية on_font_substituted"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "الحدث الذي يُطلق عندما لا يكون الخط المشار إليه في المستند المصدر متاحًا ويتم استبداله (إما بواسطة قاعدة FontSubstitute التي يوفرها العميل، أو بواسطة الخط الافتراضي المُكوَّن، أو بواسطة …"
type: docs
url: /ar/python-net/groupdocs.conversion/conversionevents/on_font_substituted/
is_root: false
weight: 2070
---


## on_font_substituted property

يُطلق الحدث عندما لا يكون الخط المشار إليه في المستند المصدر متاحًا ويتم استبداله (إما بواسطة قاعدة [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) التي يوفرها العميل، أو بواسطة الخط الافتراضي المُكوَّن، أو بواسطة آلية fallback الداخلية لأنابيب التحويل).

يتم إزالة التكرار للحدث حسب `(SourceFileName, OriginalFontName)` داخل استدعاء واحد لـ `Converter.Convert(...)` — يتلقى المشتركون إشعارًا واحدًا على الأكثر لكل خط مفقود في كل مستند مصدر. يُطلق بشكل متزامن على خيط التحويل. لا يُطلق في تحويلات الصور.

بالنسبة لمستندات العروض التقديمية، يتم اكتشاف استبدال الخطوط فقط على نظام Windows، لأن المحرك يحلها عبر مطابقة خطوط خاصة بالمنصة غير متوفرة على أنظمة تشغيل أخرى.

### Definition:
```python
@property
def on_font_substituted(self):
    ...
@on_font_substituted.setter
def on_font_substituted(self, value):
    ...
```

### انظر أيضًا
* class [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/)
