---
title: EmailLoadOptions
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: Eposta belgelerini yüklemek için seçenekler.
type: docs
weight: 2110
url: /tr/net/groupdocs.conversion.options.load/emailloadoptions/
---
## EmailLoadOptions class

E-posta belgelerini yüklemek için seçenekler.

```csharp
public sealed class EmailLoadOptions : LoadOptions, IDocumentsContainerLoadOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmailLoadOptions](emailloadoptions)() | Yeni örneğini başlatır[`EmailLoadOptions`](../emailloadoptions) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ConvertOwned](../../groupdocs.conversion.options.load/emailloadoptions/convertowned) { get; set; } | Belgeler kapsayıcısındaki sahip olunan belgelerin dönüştürülmesi gerekip gerekmediğini kontrol etme seçeneği |
| [ConvertOwner](../../groupdocs.conversion.options.load/emailloadoptions/convertowner) { get; set; } | Belge kabının kendisinin dönüştürülmesi gerekip gerekmediğini kontrol etme seçeneği Bu özellik doğruysa, belge kabı dönüştürülen ilk belge olacaktır |
| [Depth](../../groupdocs.conversion.options.load/emailloadoptions/depth) { get; set; } | Dönüşümün kaç düzeyde derinlemesine gerçekleştirileceğini kontrol etme seçeneği |
| [DisplayBccEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaybccemailaddress) { get; set; } | "Gizli" e-posta adresini görüntüleme veya gizleme seçeneği. Varsayılan: false. |
| [DisplayCcEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayccemailaddress) { get; set; } | "Cc" e-posta adresini görüntüleme veya gizleme seçeneği. Varsayılan: false. |
| [DisplayEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayemailaddress) { get; set; } | E-posta adresini görüntüleme veya gizleme seçeneği. Varsayılan: true. |
| [DisplayFromEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayfromemailaddress) { get; set; } | "Kimden" e-posta adresini görüntüleme veya gizleme seçeneği. Varsayılan: true. |
| [DisplayHeader](../../groupdocs.conversion.options.load/emailloadoptions/displayheader) { get; set; } | E-posta başlığını görüntüleme veya gizleme seçeneği. Varsayılan: true. |
| [DisplayToEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaytoemailaddress) { get; set; } | "Kime" e-posta adresini görüntüleme veya gizleme seçeneği. Varsayılan: true. |
| [FieldTextMap](../../groupdocs.conversion.options.load/emailloadoptions/fieldtextmap) { get; set; } | E-posta mesajı arasındaki eşleme[`EmailField`](../emailfield) ve alan metni gösterimi |
| [Format](../../groupdocs.conversion.options.load/emailloadoptions/format) { get; set; } | Girdi belgesi dosya türü. |
| [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Girdi belgesi dosya türü. |
| [PreserveOriginalDate](../../groupdocs.conversion.options.load/emailloadoptions/preserveoriginaldate) { get; set; } | Kaydederken posta iletisinde orijinal tarih başlığı dizesinin tutulması gerekip gerekmediğini tanımlar (Varsayılan değer doğrudur) |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/emailloadoptions/resourceloadingtimeout) { get; set; } | Harici kaynakları yüklemek için zaman aşımı |
| [TimeZoneOffset](../../groupdocs.conversion.options.load/emailloadoptions/timezoneoffset) { get; set; } | Mesaj tarihleri için Eşgüdümlü Evrensel Zaman (UTC) farkını alır veya ayarlar. Bu özellik, yerel saat ile UTC. arasındaki saat dilimi farkını tanımlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/emailloadoptions/clone)() | Geçerli örneği klonlar. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Varsayılan hash işlevi olarak işlev görür. |

### Ayrıca bakınız

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* ad alanı [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* toplantı [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
