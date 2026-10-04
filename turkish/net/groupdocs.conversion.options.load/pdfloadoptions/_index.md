---
title: "PdfLoadOptions"
second_title: "GroupDocs.Conversion for .NET API Referansı"
description: "Pdf belgelerini yükleme seçenekleri."
type: docs
weight: 2740
url: /tr/net/groupdocs.conversion.options.load/pdfloadoptions/
---
## PdfLoadOptions class

Pdf belgelerini yükleme seçenekleri.

```csharp
public sealed class PdfLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageNumberingLoadOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PdfLoadOptions](pdfloadoptions)() | Yeni bir [`PdfLoadOptions`](../pdfloadoptions) sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/pdfloadoptions/clearbuiltindocumentproperties) { get; set; } | Belgeden yerleşik meta veri özelliklerini kaldırır. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/pdfloadoptions/clearcustomdocumentproperties) { get; set; } | Belgeden özel meta veri özelliklerini kaldırır. |
| [ConvertOwned](../../groupdocs.conversion.options.load/pdfloadoptions/convertowned) { get; set; } | Uygular [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Varsayılan: false |
| [ConvertOwner](../../groupdocs.conversion.options.load/pdfloadoptions/convertowner) { get; set; } | Uygular [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Varsayılan: true |
| [DefaultFont](../../groupdocs.conversion.options.load/pdfloadoptions/defaultfont) { get; set; } | Pdf belgesi için varsayılan yazı tipi. Bir yazı tipi eksik olduğunda aşağıdaki yazı tipi kullanılacaktır. |
| [Depth](../../groupdocs.conversion.options.load/pdfloadoptions/depth) { get; set; } | Uygular [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Varsayılan: 1 |
| [FlattenAllFields](../../groupdocs.conversion.options.load/pdfloadoptions/flattenallfields) { get; set; } | PDF formundaki tüm alanları düzleştir. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/pdfloadoptions/fontsubstitutes) { get; set; } | Pdf belgesi dönüştürülürken belirli yazı tiplerini değiştir. |
| [FontTransformations](../../groupdocs.conversion.options.load/pdfloadoptions/fonttransformations) { get; set; } | Belge yüklendikten ve yazı tipi değişimi tamamlandıktan sonra mevcut yazı tiplerini dönüştürür. Yazı tipi dönüşümleri, belge içindeki tüm yazı tiplerini, başarılı bir şekilde yüklenenler dahil, değiştirebilir. |
| [Format](../../groupdocs.conversion.options.load/pdfloadoptions/format) { get; } | Girdi belge dosya türü. Bir format ayarlanana kadar `null` olur, bu yüzden `null` olup olmadığını test edin, [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) ile karşılaştırmak yerine, çünkü asla ona eşit değildir. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Girdi belge dosya türü. |
| [HidePdfAnnotations](../../groupdocs.conversion.options.load/pdfloadoptions/hidepdfannotations) { get; set; } | Pdf belgelerinde açıklamaları gizle. |
| [PageNumbering](../../groupdocs.conversion.options.load/pdfloadoptions/pagenumbering) { get; set; } | Dönüştürülen belgede sayfa numaralandırma oluşturulmasını etkinleştirir veya devre dışı bırakır. Varsayılan: false |
| [Password](../../groupdocs.conversion.options.load/pdfloadoptions/password) { get; set; } | Korunan belgeyi korumasız hâle getirmek için şifre ayarlar. |
| [RemoveEmbeddedFiles](../../groupdocs.conversion.options.load/pdfloadoptions/removeembeddedfiles) { get; set; } | Gömülü dosyaları kaldır. |
| [RemoveJavascript](../../groupdocs.conversion.options.load/pdfloadoptions/removejavascript) { get; set; } | Javascript'ı kaldır. |
| [ResetFontFolders](../../groupdocs.conversion.options.load/pdfloadoptions/resetfontfolders) { get; set; } | Belgeyi yüklemeden önce yazı tipi klasörlerini sıfırla |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Varsayılan hash işlevi olarak hizmet eder. |

### Ayrıca Bakınız

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
