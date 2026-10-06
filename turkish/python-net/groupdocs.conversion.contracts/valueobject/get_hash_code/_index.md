---
title: "get_hash_code yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Varsayılan karma işlevi olarak hizmet verir."
type: docs
url: /tr/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/
is_root: false
weight: 1040
---


## get_hash_code

Varsayılan karma işlevi olarak hizmet verir.

Array, list ve dictionary bileşenleri içeriklerine göre hash'lenir, eşitliğin onları nasıl karşılaştırdığıyla eşleşir, böylece eşit olarak karşılaştırılan iki nesne de aynı şekilde hash'lenir ve sözlük anahtarları ya da küme üyeleri olarak kullanılabilir.

Bu, başka bir `System.Collections.IEnumerable` olan bir bileşene UYGULANMAZ: böyle bir bileşen referansına göre hash'lenir ve tembel bir yineleyici olarak ortaya çıkan bir bileşen her erişimde farklı bir değer üretir, bu yüzden onu taşıyan bir nesne hiç anahtar olarak kullanılamaz. İç içe koleksiyonlar da aynı şekilde referansa göre karşılaştırılır ve hash'lenir, yinelemeli olarak değil.

Diğer sonuç, bir değer nesnesinin ortaya çıkardığı bir koleksiyonu değiştirmektir - bir sayfa listesine ekleme yapmak ya da bir düzen‑ad dizisine yazmak - bu nesnenin hash'ini değiştirir, böylece hash kapsayıcısına önceden eklenmiş bir örnek erişilemez hâle gelir. Bir değer nesnesini anahtar olarak kullanıldıktan sonra donmuş gibi davranın.

```python
def get_hash_code(self):
    ...
```

**Returns:** A hash code for the current object.

### Ayrıca Bakınız
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)
