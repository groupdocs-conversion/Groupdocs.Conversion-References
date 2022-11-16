---
title: MboxLoadOptions
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: Mbox belgelerini yükleme seçenekleri.
type: docs
weight: 1950
url: /tr/net/groupdocs.conversion.options.load/mboxloadoptions/
---
## MboxLoadOptions class

Mbox belgelerini yükleme seçenekleri.

```csharp
public sealed class MboxLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [MboxLoadOptions](mboxloadoptions)() | Yeni örneğini başlatır[`MboxLoadOptions`](../mboxloadoptions) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/mboxloadoptions/convertowned) { get; } | Belge kapsayıcısındaki sahip olunan belgelerin dönüştürülmesi gerekip gerekmediğini kontrol etme seçeneği |
| [ConvertOwner](../../groupdocs.conversion.options.load/mboxloadoptions/convertowner) { get; } | Belge kabının kendisinin dönüştürülmesi gerekip gerekmediğini kontrol etme seçeneği Bu özellik doğruysa, belge kabı dönüştürülen ilk belge olur |
| [Depth](../../groupdocs.conversion.options.load/mboxloadoptions/depth) { get; set; } | Dönüştürmeyi gerçekleştirmek için derinlemesine kaç seviyeyi kontrol etme seçeneği |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Girdi belgesi dosya türü. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/mboxloadoptions/clone)() | Geçerli örneği klonlar. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Varsayılan hash işlevi olarak işlev görür. |

### Ayrıca bakınız

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* ad alanı [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* toplantı [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->