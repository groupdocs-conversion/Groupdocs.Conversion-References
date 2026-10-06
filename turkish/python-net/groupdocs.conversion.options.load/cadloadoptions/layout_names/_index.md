---
title: "layout_names özelliği"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüştürülecek düzen adları."
type: docs
url: /tr/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/
is_root: false
weight: 2060
---


## layout_names property

Dönüştürülecek düzen adları.

PDF/UA-1'e dönüştürürken dikkate alınmaz. Bu hedef, çizimi tek bir etiketli sayfa olarak render eder; bu, seçilen her düzen için bir sayfa taşıyamaz, bu yüzden bütün çizim yerine dönüştürülür ve burada hiçbir şey uygulanmaz.

PDF dahil olmak üzere diğer tüm hedefler seçimi kabul eder. Bu hedeflerde, adlar çizimin taşıdığı düzenlere tam olarak eşleştirilir, bu yüzden yalnızca büyük/küçük harf farkı olan bir ad farklı bir ad olarak kabul edilir. Hiçbir şeyle eşleşmeyen bir ad atılır ve çağırana sadece o sayfa maliyetini getirir; hiçbir eşleşme bulunmadığı bir liste, eksik kalan adları ve çizimin taşıdığı düzenleri adlandıran bir `InvalidLoadOptionsException` ile dönüşümü başarısız kılar, çağıranın istemediği sayfaları render etmek yerine. Hiç düzen taşımayan bir çizim istisna sayılır: eşleşecek bir ad olmadığı için hiçbir şey reddedilmez.

### Definition:
```python
@property
def layout_names(self):
    ...
@layout_names.setter
def layout_names(self, value):
    ...
```

### Ayrıca Bakınız
* class [`CadLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/)
