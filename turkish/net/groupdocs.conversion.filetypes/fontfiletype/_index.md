---
title: "FontFileType"
second_title: "GroupDocs.Conversion for .NET API Referansı"
description: "Font belgelerini tanımlar Aşağıdaki türleri içerir Ttf./fontfiletype/ttfEot./fontfiletype/eotOtf./fontfiletype/otfCff./fontfiletype/cffType1./fontfiletype/type1Woff./fontfiletype/woffWoff2./fontfiletype/woff2 Font formatları hakkında daha fazla bilgi edinin buradahttps//docs.fileformat.com/font/."
type: docs
weight: 1150
url: /tr/net/groupdocs.conversion.filetypes/fontfiletype/
---
## FontFileType class

Font belgelerini tanımlar Aşağıdaki türleri içerir: [`Ttf`](./ttf)[`Eot`](./eot)[`Otf`](./otf)[`Cff`](./cff)[`Type1`](./type1)[`Woff`](./woff)[`Woff2`](./woff2) Font formatları hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/font/).

```csharp
public sealed class FontFileType : FileType
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [FontFileType](fontfiletype)() | Serileştirme yapıcısı |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Dosya türü açıklaması |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Dosya uzantısı |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Dosya ailesi |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Dosya formatı |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Mevcut nesneyi diğerine karşılaştırır. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) uygular. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Varsayılan hash işlevi olarak hizmet eder. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Dize temsili |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| static readonly [Cff](../../groupdocs.conversion.filetypes/fontfiletype/cff) | .cff uzantılı bir dosya, Compact Font Format (Kompakt Yazı Tipi Biçimi) olup aynı zamanda PostScript Type 1 veya CIDFont olarak da bilinir. CFF, bir FontSet olarak bilinen tek bir birimde birden fazla yazı tipini depolayan bir kapsayıcı görevi görür. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/font/cff/). |
| static readonly [Eot](../../groupdocs.conversion.filetypes/fontfiletype/eot) | .eot uzantılı bir dosya, bir belgeye gömülmüş OpenType yazı tipidir. Bunlar çoğunlukla bir Web sayfası gibi web dosyalarında kullanılır. Microsoft tarafından oluşturulmuş ve PowerPoint sunumu .pps dosyası dahil Microsoft ürünleri tarafından desteklenir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/font/eot/). |
| static readonly [Otf](../../groupdocs.conversion.filetypes/fontfiletype/otf) | .otf uzantılı bir dosya, OpenType yazı tipi formatına işaret eder. OTF yazı tipi formatı daha ölçeklenebilirdir ve dijital tipografi için TTF formatlarının mevcut özelliklerini genişletir. Microsoft ve Adobe tarafından geliştirilen OTF, PostScript ve TrueType yazı tipi formatlarının özelliklerini birleştirir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/font/otf/). |
| static readonly [Ttf](../../groupdocs.conversion.filetypes/fontfiletype/ttf) | .ttf uzantılı bir dosya, TrueType spesifikasyonlarına dayanan yazı tipi dosyalarını temsil eder. İlk olarak Apple Computer, Inc. tarafından Mac OS için tasarlanıp piyasaya sürülmüş ve daha sonra Microsoft tarafından Windows OS için benimsenmiştir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/font/ttf/). |
| static readonly [Type1](../../groupdocs.conversion.filetypes/fontfiletype/type1) | Type 1 yazı tipleri, PostScript kullanabilen masaüstü yayıncılık yazılımları ve yazıcılar tarafından yaygın olarak kullanılan, artık kullanılmayan bir Adobe teknolojisidir. Type 1 yazı tipleri birçok modern platform, web tarayıcısı ve mobil işletim sistemi tarafından desteklenmese de, bazı işletim sistemlerinde hâlâ desteklenmektedir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/font/type1/). |
| static readonly [Woff](../../groupdocs.conversion.filetypes/fontfiletype/woff) | .woff uzantılı bir dosya, Web Open Font Format (WOFF) tabanlı bir web yazı tipi dosyasıdır. TrueType (.TTF) veya OpenType (.OTT) yazı tipi türlerinden birine dayalı format‑özel sıkıştırılmış bir kapsayıcıya sahiptir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/font/woff/). |
| static readonly [Woff2](../../groupdocs.conversion.filetypes/fontfiletype/woff2) | .woff uzantılı bir dosya, Web Open Font Format (WOFF) tabanlı bir web yazı tipi dosyasıdır. TrueType (.TTF) veya OpenType (.OTT) yazı tipi türlerinden birine dayalı format‑özel sıkıştırılmış bir kapsayıcıya sahiptir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/font/woff/). |

### Ayrıca Bakınız

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
