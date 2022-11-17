---
title: WordProcessingConvertOptions
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: WordProcessing dosya türüne dönüştürme seçenekleri.
type: docs
weight: 1810
url: /tr/net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
## WordProcessingConvertOptions class

WordProcessing dosya türüne dönüştürme seçenekleri.

```csharp
public class WordProcessingConvertOptions : CommonConvertOptions<WordProcessingFileType>, 
    IPageMarginConvertOptions, IPageOrientationConvertOptions, IPageSizeConvertOptions, 
    IPdfRecognitionModeOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [WordProcessingConvertOptions](wordprocessingconvertoptions)() | Yeni örneğini başlatır[`WordProcessingConvertOptions`](../wordprocessingconvertoptions) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Dpi](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/dpi) { get; set; } | Dönüştürmeden sonra istenen sayfa DPI. Varsayılan çözünürlük: 96 dpi. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | Girdi belgesinin dönüştürülmesi gereken istenen dosya türü. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | Girdi belgesinin dönüştürülmesi gereken istenen dosya türü. |
| [Height](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/height) { get; set; } | Dönüşümden sonra istenen sayfa yüksekliği. |
| [MarginBottom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginbottom) { get; set; } | Dönüştürmeden sonra piksel cinsinden istenen sayfa alt kenar boşluğu. |
| [MarginLeft](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginleft) { get; set; } | Dönüştürmeden sonra istenen sayfa sol kenar boşluğu piksel cinsinden. |
| [MarginRight](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/marginright) { get; set; } | Dönüştürmeden sonra piksel cinsinden istenen sayfa sağ marjı. |
| [MarginTop](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/margintop) { get; set; } | Dönüştürmeden sonra piksel cinsinden istenen sayfa üst kenar boşluğu. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | Dönüşümün başlatılacağı sayfa numarası. |
| [PageOrientation](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pageorientation) { get; set; } | Dönüştürmeden sonra istenen sayfa yönlendirmesi |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | Dönüştürülecek sayfa dizinlerinin listesi. Belirli sayfaları dönüştürmek için belirtilmelidir. |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | Başlangıç olarak dönüştürülecek sayfa sayısı`Sayfa numarası` . |
| [PageSize](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pagesize) { get; set; } | Dönüşümden sonra istenen sayfa boyutu |
| [Password](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/password) { get; set; } | Dönüştürülen belgeyi bir parola ile korumak istiyorsanız bu özelliği ayarlayın. |
| [PdfRecognitionMode](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/pdfrecognitionmode) { get; set; } | pdf 'den dönüştürürken tanıma modu |
| [RtfOptions](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/rtfoptions) { get; set; } | RTF'ye özel dönüştürme seçenekleri |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | Filigrana özel seçenekler |
| [Width](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/width) { get; set; } | Dönüştürmeden sonra istenen sayfa genişliği. |
| [Zoom](../../groupdocs.conversion.options.convert/wordprocessingconvertoptions/zoom) { get; set; } | Yakınlaştırma düzeyini yüzde olarak belirtir. Varsayılan 100. Varsayılan yakınlaştırma Microsoft Word 2010'a kadar desteklenir. Microsoft Word 2013'ten itibaren varsayılan yakınlaştırma artık belge olarak ayarlanmamıştır, bunun yerine açılan son belgenin yakınlaştırma faktörünü kullanıyor gibi görünmektedir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | Geçerli seçenekler örneğini kopyalar. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Varsayılan hash işlevi olarak işlev görür. |

### Ayrıca bakınız

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [WordProcessingFileType](../../groupdocs.conversion.filetypes/wordprocessingfiletype)
* interface [IPageMarginConvertOptions](../ipagemarginconvertoptions)
* interface [IPageOrientationConvertOptions](../ipageorientationconvertoptions)
* interface [IPageSizeConvertOptions](../ipagesizeconvertoptions)
* interface [IPdfRecognitionModeOptions](../ipdfrecognitionmodeoptions)
* ad alanı [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* toplantı [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
