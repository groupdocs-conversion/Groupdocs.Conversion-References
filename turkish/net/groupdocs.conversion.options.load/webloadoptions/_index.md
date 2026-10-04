---
title: "WebLoadOptions"
second_title: "GroupDocs.Conversion for .NET API Referansı"
description: "Web belgelerini yükleme seçenekleri."
type: docs
weight: 2920
url: /tr/net/groupdocs.conversion.options.load/webloadoptions/
---
## WebLoadOptions class

Web belgelerini yükleme seçenekleri.

```csharp
public class WebLoadOptions : LoadOptions, ICustomCssStyleOptions, IPageLayoutOptions, 
    IPageMarginOptions, IPageNumberingLoadOptions, IPageOrientationOptions, IPageSizeOptions, 
    IResourceLoadingOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [WebLoadOptions](webloadoptions)() | Yeni bir [`WebLoadOptions`](../webloadoptions) sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BasePath](../../groupdocs.conversion.options.load/webloadoptions/basepath) { get; set; } | HTML için temel yol/url |
| [ConfigureHeaders](../../groupdocs.conversion.options.load/webloadoptions/configureheaders) { get; set; } | İstek başlıklarının yapılandırması için eylem. Eylemin ilk parametresi Uri'dir. |
| [CredentialsProvider](../../groupdocs.conversion.options.load/webloadoptions/credentialsprovider) { get; set; } | Uri için kimlik bilgileri sağlayıcısı. |
| [CustomCssStyle](../../groupdocs.conversion.options.load/webloadoptions/customcssstyle) { get; set; } | [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) uygular. |
| [Encoding](../../groupdocs.conversion.options.load/webloadoptions/encoding) { get; set; } | Web belgesi yüklenirken kullanılacak kodlamayı alır veya ayarlar. Özellik null ise kodlama, belgenin karakter kümesi özniteliğinden belirlenir. |
| [Format](../../groupdocs.conversion.options.load/webloadoptions/format) { get; set; } | Girdi belge dosya türü. Bir format ayarlanana kadar `null` olur, bu yüzden `null` olup olmadığını test edin, [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) ile karşılaştırmak yerine, çünkü asla ona eşit değildir. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Girdi belge dosya türü. |
| [HtmlRenderingMode](../../groupdocs.conversion.options.load/webloadoptions/htmlrenderingmode) { get; set; } | HTML içeriğinin nasıl render edildiğini kontrol eder. Varsayılan: AbsolutePositioning |
| [MarginSettings](../../groupdocs.conversion.options.load/webloadoptions/marginsettings) { get; set; } | Sayfa kenar boşluğu ayarları |
| [OrientationSettings](../../groupdocs.conversion.options.load/webloadoptions/orientationsettings) { get; set; } | Sayfa yönlendirme ayarları |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/webloadoptions/pagelayoutoptions) { get; set; } | Web belgeleri yüklenirken sayfa düzeni seçeneklerini belirtir. |
| [PageNumbering](../../groupdocs.conversion.options.load/webloadoptions/pagenumbering) { get; set; } | Dönüştürülen belgede sayfa numaralandırma oluşturulmasını etkinleştirir veya devre dışı bırakır. Varsayılan: false |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/webloadoptions/resourceloadingtimeout) { get; set; } | Harici kaynakların yüklenmesi için zaman aşımı |
| [SizeSettings](../../groupdocs.conversion.options.load/webloadoptions/sizesettings) { get; set; } | Sayfa boyutu ayarları |
| [SkipExternalResources](../../groupdocs.conversion.options.load/webloadoptions/skipexternalresources) { get; set; } | Uygular [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UsePdf](../../groupdocs.conversion.options.load/webloadoptions/usepdf) { get; set; } | Dönüştürme için pdf kullan. Varsayılan: false |
| [WhitelistedResources](../../groupdocs.conversion.options.load/webloadoptions/whitelistedresources) { get; set; } | Uygular [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |
| [Zoom](../../groupdocs.conversion.options.load/webloadoptions/zoom) { get; set; } | Yakınlaştırma seviyesini yüzde olarak belirtir. Yakınlaştırma seviyesi, dönüşümden önce belgenin &lt;body&gt; etiketine uygulanır ve belgenin görsel görünümünü ölçeklendirir. %100 değeri orijinal boyutu temsil eder. Varsayılan değer 100'dür. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Varsayılan hash işlevi olarak hizmet eder. |

### Ayrıca Bakınız

* class [LoadOptions](../loadoptions)
* interface [ICustomCssStyleOptions](../icustomcssstyleoptions)
* interface [IPageLayoutOptions](../ipagelayoutoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
