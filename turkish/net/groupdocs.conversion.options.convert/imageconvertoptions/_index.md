---
title: ImageConvertOptions
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: Görüntü dosyası türüne dönüştürme seçenekleri.
type: docs
weight: 1630
url: /tr/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

Görüntü dosyası türüne dönüştürme seçenekleri.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | Yeni örneğini başlatır[`ImageConvertOptions`](../imageconvertoptions) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | Kaynak format tarafından desteklenen yerlerde arka plan rengini ayarlar |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | Görüntü parlaklığını ayarlar. |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | Görüntü kontrastını ayarlar. |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | Görüntü çevirme modu. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Girdi belgesinin dönüştürülmesi gereken istenen dosya türü. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Girdi belgesinin dönüştürülmesi gereken istenen dosya türü. |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | Görüntü gammasını ayarlar. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | Gri tonlamalı görüntüye dönüştürülüp dönüştürülmeyeceğini belirtir. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | Dönüştürmeden sonra istenen görüntü yüksekliği. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | Dönüştürmeden sonra istenen görüntü yatay çözünürlüğü. Varsayılan çözünürlük, giriş dosyasının çözünürlüğü veya 96 dpi. 'dir. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Jpeg'e özgü dönüştürme seçenekleri. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Dönüşümün başlatılacağı sayfa numarası. |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Dönüştürülecek sayfa dizinlerinin listesi. Belirli sayfaları dönüştürmek için belirtilmelidir. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Başlangıç olarak dönüştürülecek sayfa sayısı`Sayfa numarası` . |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Psd'ye özgü dönüştürme seçenekleri. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | Görüntü döndürme açısı. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Tiff'e özgü dönüştürme seçenekleri. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | Eğer`doğru` , giriş önce PDF'ye ve ardından istenen formata dönüştürülür. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | Dönüştürmeden sonra istenen görüntü dikey çözünürlüğü. Varsayılan çözünürlük, giriş dosyasının çözünürlüğü veya 96 dpi. 'dir. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Filigrana özel seçenekler |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Webp'e özgü dönüştürme seçenekleri. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | Dönüştürmeden sonra istenen görüntü genişliği. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Geçerli seçenekler örneğini kopyalar. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Varsayılan hash işlevi olarak işlev görür. |

### Ayrıca bakınız

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* ad alanı [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* toplantı [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
