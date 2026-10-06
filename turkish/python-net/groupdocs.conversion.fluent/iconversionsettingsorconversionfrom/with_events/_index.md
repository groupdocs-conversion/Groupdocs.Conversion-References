---
title: "with_events yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Dönüştürücünün ömrü boyunca var olan ve her dönüşüm çalıştırmasında tetiklenen bir ConversionEvents çantası üzerindeki dönüşüm yaşam döngüsü olay işleyicilerini kaydeder."
type: docs
url: /tr/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/with_events/
is_root: false
weight: 1070
---


## with_events {#configure}

Dönüştürücünün ömrü boyunca var olan ve her dönüşüm çalıştırıldığında tetiklenen bir [`ConversionEvents`](/conversion/python-net/groupdocs.conversion/conversionevents/) çantası üzerine dönüşüm yaşam döngüsü olay işleyicilerini kaydeder.

Bu, [`IConversionSettings.with_settings`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettings/with_settings/) ile aynı giriş aşamasında bulunur. Birden fazla çağrı birikir: aynı iç çanta her `configure` eylemine geçirilir, böylece daha erken çağrılarda ayarlanan işleyiciler, daha sonraki bir çağrı tarafından üzerine yazılmadıkça korunur.

```python
def with_events(self, configure):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| configure | `Action[ConversionEvents]` | Olay çantasını değiştiren eylem. |

**Returns:** The source-selection stage so that `Load` may be chained.

### Ayrıca Bakınız
* class [`IConversionSettingsOrConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionsettingsorconversionfrom/)
