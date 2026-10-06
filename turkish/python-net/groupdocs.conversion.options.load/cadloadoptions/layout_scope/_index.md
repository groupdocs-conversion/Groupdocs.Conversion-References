---
title: "layout_scope özelliği"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüştürülen çizim alanlarını belirleyen layout kapsamı."
type: docs
url: /tr/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/
is_root: false
weight: 2070
---


## layout_scope property

Çizim alanlarının hangi bölümlerinin dönüştürüleceğini belirleyen düzen kapsamı. Varsayılan olarak [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/) kullanılır, bu dönüşümü kısıtlamaz. [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) sağlandığında yok sayılır, çünkü açık düzen adları her zaman önceliklidir. Bir `None` değeri [`CadLayoutScope.both`](/conversion/python-net/groupdocs.conversion.options.load/cadlayoutscope/) olarak ele alınır.

Eğer kapsam, bir çizim tarafından sunulan sayfalardan hiçbirini seçmezse, dönüşüm `InvalidLoadOptionsException` hatasıyla başarısız olur; bu hata kapsamı ve mevcut sayfaları, dışarı bırakılan alanları render etmek yerine adlandırır. Hiç sayfa sunmayan bir çizim etkilenmez ve tek bir birim olarak dönüştürülmeye devam eder. PDF/UA-1'e dönüştürürken dikkate alınmaz; bunun nedeni [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) adresinde verilen açıklamadır.

### Definition:
```python
@property
def layout_scope(self):
    ...
@layout_scope.setter
def layout_scope(self, value):
    ...
```

### Ayrıca Bakınız
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
