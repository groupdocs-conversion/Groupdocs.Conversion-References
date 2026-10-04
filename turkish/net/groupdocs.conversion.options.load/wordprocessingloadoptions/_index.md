---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion for .NET API Referansı"
description: "WordProcessing belgelerini yükleme seçenekleri."
type: docs
weight: 2950
url: /tr/net/groupdocs.conversion.options.load/wordprocessingloadoptions/
---
## WordProcessingLoadOptions class

WordProcessing belgelerini yükleme seçenekleri.

```csharp
public class WordProcessingLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageMarginOptions, IPageNumberingLoadOptions, IPageSizeOptions, IResourceLoadingOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [WordProcessingLoadOptions](wordprocessingloadoptions)() | [`WordProcessingLoadOptions`](../wordprocessingloadoptions) sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AutoDetectRtlDirection](../../groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection) { get; set; } | Doğru (varsayılan) olduğunda, metni büyük ölçüde sağdan sola olan paragraflar ve koşular, dönüştürmeden önce bidi bayrakları onarılır. Bu, Microsoft Word ve LibreOffice'in uyguladığı sezgiyi eşleştirir ve yalnızca RTL betiği içeren koşularda &lt;w:bidi/&gt; olmadan ve &lt;w:rtl w:val="0"/&gt; ile OOXML üreten jeneratörlerin (özellikle Google Docs) oluşturduğu Arapça/İbranice belgelerin renderlanmasını düzeltir. false olarak ayarlandığında, kaynak işaretlemenin katı OOXML yorumlamasını korur. |
| [BookmarkOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/bookmarkoptions) { get; set; } | Yer imi seçenekleri |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearbuiltindocumentproperties) { get; set; } | Belgeden yerleşik meta veri özelliklerini kaldırır. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearcustomdocumentproperties) { get; set; } | Belgeden özel meta veri özelliklerini kaldırır. |
| [CommentDisplayMode](../../groupdocs.conversion.options.load/wordprocessingloadoptions/commentdisplaymode) { get; set; } | Yorumların çıktı belgesinde nasıl görüntüleneceğini belirtir. Varsayılan ShowInBalloons'dir. |
| [ConvertOwned](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowned) { get; set; } | Uygular [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) Varsayılan: false |
| [ConvertOwner](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowner) { get; set; } | Uygular [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) Varsayılan: true |
| [DefaultFont](../../groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont) { get; set; } | Bir WordProcessing belgesi için varsayılan yazı tipini ayarlar. |
| [Depth](../../groupdocs.conversion.options.load/wordprocessingloadoptions/depth) { get; set; } | Uygular [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) Varsayılan: 1 |
| [EmbedTrueTypeFonts](../../groupdocs.conversion.options.load/wordprocessingloadoptions/embedtruetypefonts) { get; set; } | EmbedTrueTypeFonts true ise, GroupDocs.Conversion çıktı belgesine TrueType yazı tiplerini gömer. Varsayılan: true |
| [FontConfigSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontconfigsubstitutionenabled) { get; set; } | Sistemdeki FontConfig temel alınarak eksik yazı tipleri otomatik olarak değiştirilir. Varsayılan: false. |
| [FontInfoSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontinfosubstitutionenabled) { get; set; } | Belgedeki FontInfo temel alınarak eksik yazı tipleri otomatik olarak değiştirilir. Varsayılan: false. |
| [FontNameSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontnamesubstitutionenabled) { get; set; } | Yazı tipi adına göre eksik yazı tipleri otomatik olarak değiştirilir. Varsayılan: false. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes) { get; set; } | WordsProcessing belgesi dönüştürülürken belirli yazı tiplerini değiştirir. |
| [FontTransformations](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fonttransformations) { get; set; } | Belge yüklendikten ve yazı tipi değişimi tamamlandıktan sonra mevcut yazı tiplerini dönüştürür. Yazı tipi dönüşümleri, belge içindeki tüm yazı tiplerini, başarılı bir şekilde yüklenenler dahil, değiştirebilir. |
| [Format](../../groupdocs.conversion.options.load/wordprocessingloadoptions/format) { get; set; } | Girdi belge dosya türü. Bir format ayarlanana kadar `null` olur, bu yüzden `null` olup olmadığını test edin, [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) ile karşılaştırmak yerine, çünkü asla ona eşit değildir. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Girdi belge dosya türü. |
| [HideWordTrackedChanges](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hidewordtrackedchanges) { get; set; } | Word belgeleri için işaretlemeyi gizler ve değişiklikleri izler. |
| [HyphenationOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenationoptions) { get; set; } | WordProcessing belgeleri için heceleme seçeneklerini ayarlar. |
| [KeepDateFieldOriginalValue](../../groupdocs.conversion.options.load/wordprocessingloadoptions/keepdatefieldoriginalvalue) { get; set; } | Tarih alanının orijinal değerini korur. Varsayılan: false |
| [MarginSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/marginsettings) { get; set; } | Sayfa kenar boşluğu ayarları |
| [PageNumbering](../../groupdocs.conversion.options.load/wordprocessingloadoptions/pagenumbering) { get; set; } | Dönüştürülen belgede sayfa numaralandırma oluşturulmasını etkinleştirir veya devre dışı bırakır. Varsayılan: false |
| [Password](../../groupdocs.conversion.options.load/wordprocessingloadoptions/password) { get; set; } | Korunan belgeyi korumasız hâle getirmek için şifre ayarlar. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preservedocumentstructure) { get; set; } | PDF'ye dönüştürülürken belge yapısının korunup korunmayacağını belirler (varsayılan false). |
| [PreserveFormFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preserveformfields) { get; set; } | Microsoft Word form alanlarının PDF'de form alanı olarak korunup korunmayacağını veya metne dönüştürülüp dönüştürülmeyeceğini belirtir. Varsayılan false. |
| [ShowFullCommenterName](../../groupdocs.conversion.options.load/wordprocessingloadoptions/showfullcommentername) { get; set; } | Yorumlarda tam yorumcu adını göster. Varsayılan false. |
| [SizeSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/sizesettings) { get; set; } | Sayfa boyutu ayarları |
| [SkipExternalResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/skipexternalresources) { get; set; } | Uygular [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UpdateFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatefields) { get; set; } | Yükleme sonrası alanları günceller. Varsayılan: false |
| [UpdatePageLayout](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatepagelayout) { get; set; } | Yükleme sonrası sayfa düzenini günceller. Varsayılan: false |
| [UseTextShaper](../../groupdocs.conversion.options.load/wordprocessingloadoptions/usetextshaper) { get; set; } | Daha iyi kerning gösterimi için bir metin şekillendirici kullanılıp kullanılmayacağını belirtir. Varsayılan false. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/whitelistedresources) { get; set; } | Uygular [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Varsayılan hash işlevi olarak hizmet eder. |

### Açıklamalar

**Font Processing Pipeline:**

**Phase 1 - Font Substitution (during document loading):**

• Eksik/erişilemeyen yazı tiplerini FontSubstitutes, DefaultFont ve sistem ikamesi kullanarak işler

• İşleme sırası: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

**Phase 2 - Font Replacement (after document loading):**

• Yüklenen belgede mevcut olan tüm yazı tiplerini FontReplacements kullanarak değiştirir

• Tüm yazı tipi ikamesi tamamlandıktan sonra uygulanır

### Ayrıca Bakınız

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
