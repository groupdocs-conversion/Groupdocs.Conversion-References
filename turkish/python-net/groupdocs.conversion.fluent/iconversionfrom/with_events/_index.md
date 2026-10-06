---
title: "with_events yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüştürücünün ömrü boyunca var olan ve her dönüşüm çalıştırıldığında tetiklenen bir ConversionEvents çantası üzerinde dönüşüm yaşam döngüsü olay işleyicilerini kaydedin."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionfrom/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

Dönüştürücünün ömrü boyunca var olan ve her dönüşüm çalıştırıldığında tetiklenen bir [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) çantası üzerinde dönüşüm yaşam döngüsü olay işleyicilerini kaydedin.

[`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/) öncesinde veya sonrasında çağrılabilir.
Birden fazla çağrı birikir: aynı iç çanta her `configure` eylemine geçirilir, böylece önceki çağrılarda ayarlanan işleyiciler daha sonraki bir çağrı tarafından üzerine yazılmadıkça korunur.

```python
def with_events(self, configure):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Olay çantasını değiştiren eylem. |

**Returns:** This stage so that further entry-stage calls or `Load` may be chained.

### Ayrıca Bakınız
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
