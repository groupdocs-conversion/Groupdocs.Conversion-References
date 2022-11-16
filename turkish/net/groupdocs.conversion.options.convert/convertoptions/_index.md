---
title: ConvertOptions
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: Genel dönüştürme seçenekleri class.
type: docs
weight: 1330
url: /tr/net/groupdocs.conversion.options.convert/convertoptions/
---
## ConvertOptions class

Genel dönüştürme seçenekleri class.

```csharp
public abstract class ConvertOptions : ValueObject, ICloneable, IConvertOptions
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Girdi belgesinin dönüştürülmesi gereken istenen dosya türü. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Geçerli seçenekler örneğini kopyalar. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Varsayılan hash işlevi olarak işlev görür. |

### Ayrıca bakınız

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* interface [IConvertOptions](../iconvertoptions)
* ad alanı [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* toplantı [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->