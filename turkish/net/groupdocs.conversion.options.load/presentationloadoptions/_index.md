---
title: "PresentationLoadOptions"
second_title: "GroupDocs.Conversion for .NET API Referansı"
description: "Presentation belgelerini yükleme seçenekleri."
type: docs
weight: 2770
url: /tr/net/groupdocs.conversion.options.load/presentationloadoptions/
---
## PresentationLoadOptions class

Presentation belgelerini yükleme seçenekleri.

```csharp
public class PresentationLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IMetadataLoadOptions, IResourceLoadingOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PresentationLoadOptions](presentationloadoptions)() | Yeni bir [`PresentationLoadOptions`](../presentationloadoptions) sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/presentationloadoptions/clearbuiltindocumentproperties) { get; set; } | Belgeden yerleşik meta veri özelliklerini kaldırır. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/presentationloadoptions/clearcustomdocumentproperties) { get; set; } | Belgeden özel meta veri özelliklerini kaldırır. |
| [CommentsPosition](../../groupdocs.conversion.options.load/presentationloadoptions/commentsposition) { get; set; } | Yorumların slayt ile nasıl yazdırıldığını temsil eder. Varsayılan değer None'dır. |
| [ConvertOwned](../../groupdocs.conversion.options.load/presentationloadoptions/convertowned) { get; set; } | Uygular [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Varsayılan: false |
| [ConvertOwner](../../groupdocs.conversion.options.load/presentationloadoptions/convertowner) { get; set; } | Uygular [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Varsayılan: true |
| [DefaultFont](../../groupdocs.conversion.options.load/presentationloadoptions/defaultfont) { get; set; } | Sunumu renderlamak için varsayılan yazı tipi. Sunumda bir yazı tipi eksikse aşağıdaki yazı tipi kullanılacaktır. |
| [Depth](../../groupdocs.conversion.options.load/presentationloadoptions/depth) { get; set; } | Uygular [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Varsayılan: 1 |
| [FontSubstitutes](../../groupdocs.conversion.options.load/presentationloadoptions/fontsubstitutes) { get; set; } | Sunum belgesi dönüştürülürken belirli yazı tipleri ikame edilir. |
| [Format](../../groupdocs.conversion.options.load/presentationloadoptions/format) { get; set; } | Girdi belge dosya türü. Bir format ayarlanana kadar `null` olur, bu yüzden `null` olup olmadığını test edin, [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) ile karşılaştırmak yerine, çünkü asla ona eşit değildir. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Girdi belge dosya türü. |
| [NotesPosition](../../groupdocs.conversion.options.load/presentationloadoptions/notesposition) { get; set; } | Notların slayt ile nasıl yazdırıldığını temsil eder. Varsayılan değer None'dır. |
| [Password](../../groupdocs.conversion.options.load/presentationloadoptions/password) { get; set; } | Korunan belgeyi korumasız hâle getirmek için şifre ayarlar. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/presentationloadoptions/preservedocumentstructure) { get; set; } | PDF'ye dönüştürülürken belge yapısının korunup korunmayacağını belirler (varsayılan false). |
| [ShowHiddenSlides](../../groupdocs.conversion.options.load/presentationloadoptions/showhiddenslides) { get; set; } | Gizli slaytları göster. |
| [SkipExternalResources](../../groupdocs.conversion.options.load/presentationloadoptions/skipexternalresources) { get; set; } | Uygular [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [WhitelistedResources](../../groupdocs.conversion.options.load/presentationloadoptions/whitelistedresources) { get; set; } | Uygular [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Varsayılan hash işlevi olarak hizmet eder. |
| [SetVideoConnector](../../groupdocs.conversion.options.load/presentationloadoptions/setvideoconnector)(IPresentationVideoConnector) | Video belge bağlayıcısını ayarla |

### Ayrıca Bakınız

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
