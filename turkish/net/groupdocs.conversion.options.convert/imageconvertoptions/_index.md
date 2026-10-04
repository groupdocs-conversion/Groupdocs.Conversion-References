---
title: "ImageConvertOptions"
second_title: "GroupDocs.Conversion for .NET API Referansı"
description: "Görüntü dosya türüne dönüşüm seçenekleri."
type: docs
weight: 1950
url: /tr/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Görüntü dosya türüne dönüşüm seçenekleri.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>, IUsePdfConvertOptions
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Yeni bir [`ImageConvertOptions`](../imageconvertoptions) sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Kaynak formatın desteklediği yerlerde arka plan rengini ayarlar |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Görüntü parlaklığını ayarlar. |
| [CapResolutionToPageContent](../../groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent) { get; set; } | Ayarlandığında, sayfa başına PDF render çözünürlüğünü sayfanın yerel raster çözünürlüğüne sınırlar, böylece bir sayfa gömülü görüntünün gerçekte sahip olduğundan daha yüksek DPI'da işlenmez ve istenen DPI'ye yeniden büyütmek yerine sayfayı yerel (daha küçük) piksel boyutları ve yerel DPI ile nihai çıktıda yayınlar. Yalnızca görüntü ağırlıklı (tarama) sayfalar etkilenir; metin veya vektör içeriği olan sayfalar asla yumuşatılmaz ve istenen DPI'de yayınlanır. Açık bir çıktı [`Width`](./width) veya [`Height`](./height) ayarlandığında atlanır. Varsayılan değer `false` (sınırlandırma yok; her sayfa istenen DPI'de işlenir ve yayınlanır). |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Görüntü kontrastını ayarlar. |
| [CropArea](../../groupdocs.conversion.options.convert/imageconvertoptions/croparea) { get; set; } | Dönüştürmeden sonra raster görüntü alanını kırp. |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Görüntü çevirme modu. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Giriş belgesinin dönüştürülmesi gereken istenen dosya türü. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Uygular [`Format`](../iconvertoptions/format) |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Görüntü gamasını ayarlar. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Gri tonlamalı görüntüye dönüştürülüp dönüştürülmeyeceğini gösterir. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Dönüştürme sonrası istenen görüntü yüksekliği. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Dönüştürme sonrası istenen görüntü yatay çözünürlüğü. Varsayılan çözünürlük, giriş dosyasının çözünürlüğü veya 96 dpi'dir. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Jpeg'e özgü dönüştürme seçenekleri. |
| [MinResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/minresolution) { get; set; } | [`CapResolutionToPageContent`](./capresolutiontopagecontent) etkin olduğunda sınırlı render DPI'sine uygulanan eksen başına alt sınır. Sınırlı DPI bu değerin altına düşmez. Varsayılan değer `0` (alt sınır yok). |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Uygular [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Uygular [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Uygular [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Psd'ye özgü dönüştürme seçenekleri. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Görüntü döndürme açısı. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Tiff'e özgü dönüştürme seçenekleri. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | `true` ise, giriş önce PDF'ye, ardından istenen formata dönüştürülür. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Dönüştürmeden sonra istenen görüntü dikey çözünürlüğü. Varsayılan çözünürlük, giriş dosyasının çözünürlüğü veya 96 dpi'dir. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Uygular [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Webp'e özgü dönüştürme seçenekleri. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Dönüştürmeden sonra istenen görüntü genişliği. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Mevcut seçenek örneğini kopyalar. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Varsayılan hash işlevi olarak hizmet eder. |

### Ayrıca Bakınız

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
