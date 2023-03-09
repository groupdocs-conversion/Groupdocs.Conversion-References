---
title: FontFileType
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: Yazı Tipini tanımlarbelgeler Aşağıdaki türleri içerir Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 Yazı tipi biçimleri hakkında daha fazla bilgi edininBuradahttps//docs.fileformat.com/font/ .
type: docs
weight: 950
url: /tr/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

Yazı Tipini tanımlarbelgeler Aşağıdaki türleri içerir: [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) Yazı tipi biçimleri hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/font/) .

```csharp
public sealed class FontFileType : FileType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [FontFileType](fontfiletype)() | Serileştirme oluşturucu |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Dosya türü açıklaması |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Dosya uzantısı |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | family dosyası |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Dosya biçimi |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Geçerli nesneyi diğeriyle karşılaştırır. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Varsayılan hash işlevi olarak işlev görür. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Dizi gösterimi |

## Alanlar

| İsim | Tanım |
| --- | --- |
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | .cff uzantılı bir dosya, Kompakt Yazı Tipi Formatıdır ve PostScript Tip 1 veya CIDFont olarak da bilinir. CFF, FontSet olarak bilinen tek bir birimde birden çok yazı tipini bir arada depolamak için bir kap görevi görür. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/font/cff/) . |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | .eot uzantılı bir dosya, belgeye katıştırılmış bir OpenType yazı tipidir. Bunlar çoğunlukla Web sayfası gibi web dosyalarında kullanılır. Microsoft tarafından oluşturulmuştur ve PowerPoint sunumu .pps dosyası dahil olmak üzere Microsoft Ürünleri tarafından desteklenmektedir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/font/eot/) . |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | .otf uzantılı bir dosya, OpenType yazı tipi biçimini ifade eder. OTF yazı tipi biçimi daha ölçeklenebilirdir ve dijital tipografi için TTF biçimlerinin mevcut özelliklerini genişletir. Microsoft ve Adobe tarafından geliştirilen OTF, PostScript ve TrueType yazı tipi biçimlerinin özelliklerini birleştirir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/font/otf/) . |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | .ttf uzantılı bir dosya, TrueType belirtimleri yazı tipi teknolojisine dayalı yazı tipi dosyalarını temsil eder. Başlangıçta Apple Computer, Inc. tarafından Mac OS için tasarlanmış ve başlatılmıştır ve daha sonra Microsoft tarafından Windows OS için benimsenmiştir. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/font/ttf/) . |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Tip 1 yazı tipleri, masaüstü tabanlı yayıncılık yazılımlarında ve PostScript kullanabilen yazıcılarda yaygın olarak kullanılan, kullanımdan kaldırılmış bir Adobe teknolojisidir. Tip 1 yazı tipleri birçok modern platformda, web tarayıcısında ve mobil işletim sisteminde desteklenmese de bazı işletim sistemlerinde hala desteklenmektedir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/font/type1/) . |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | .woff uzantılı bir dosya, Web Açık Yazı Tipi Formatını (WOFF) temel alan bir web yazı tipi dosyasıdır. TrueType (.TTF) veya OpenType (.OTT) yazı tipi türlerine dayalı biçime özgü sıkıştırılmış kapsayıcıya sahiptir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/font/woff/) . |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | .woff uzantılı bir dosya, Web Açık Yazı Tipi Formatını (WOFF) temel alan bir web yazı tipi dosyasıdır. TrueType (.TTF) veya OpenType (.OTT) yazı tipi türlerine dayalı biçime özgü sıkıştırılmış kapsayıcıya sahiptir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/font/woff/) . |

### Ayrıca bakınız

* class [FileType](../filetype)
* ad alanı [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* toplantı [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
