---
title: PresentationFileType
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: Slaytlar şekiller metin animasyonlar video ses ve katıştırılmış nesneler gibi sunum verilerini barındırmak için kayıt koleksiyonunu depolayan Sunum dosyası biçimlerini tanımlar. Aşağıdaki dosya türlerini içerir Odp./presentationfiletype/odp  Otp./presentationfiletype/otp  Pot./presentationfiletype/pot  Potm./presentationfiletype/potm  Potx./presentationfiletype/potx  Pps./presentationfiletype/pps  Ppsm./presentationfiletype/ppsm  Ppsx./presentationfiletype/ppsx  Ppt./presentationfiletype/ppt  Pptm./presentationfiletype/pptm  Pptx./presentationfiletype/pptx . Sunum biçimleri hakkında daha fazla bilgi edininBuradahttps//wiki.fileformat.com/presentation .
type: docs
weight: 1020
url: /tr/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

Slaytlar, şekiller, metin, animasyonlar, video, ses ve katıştırılmış nesneler gibi sunum verilerini barındırmak için kayıt koleksiyonunu depolayan Sunum dosyası biçimlerini tanımlar. Aşağıdaki dosya türlerini içerir: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Pptm`](./pptm) , [`Pptx`](./pptx) . Sunum biçimleri hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/presentation) .

```csharp
public sealed class PresentationFileType : FileType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | Serileştirme oluşturucu |

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
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | FODP uzantılı dosyalar, OpenDocument Düz XML Sunumunu temsil eder. Sunum dosyası OpenDocument formatında kaydedildi, ancak standart .ODP files tarafından kullanılan .ZIP kabı yerine düz bir XML formatı kullanılarak kaydedildi. |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | ODP uzantılı dosyalar, OASISOpen standardında OpenOffice.org tarafından kullanılan sunum dosyası biçimini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | .OTP uzantılı dosyalar, uygulamalar tarafından OASIS OpenDocument standart biçiminde oluşturulan sunum şablonu dosyalarını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | .POT uzantılı dosyalar, PowerPoint 97-2003 sürümleri tarafından oluşturulan Microsoft PowerPoint şablon dosyalarını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | POTM uzantılı dosyalar, Makroları destekleyen Microsoft PowerPoint şablon dosyalarıdır. POTM dosyaları, PowerPoint 2007 veya üzeri sürümlerle oluşturulur ve daha fazla sunum dosyası oluşturmak için kullanılabilecek varsayılan ayarları içerir. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | .POTX uzantılı dosyalar, Microsoft PowerPoint 2007 ve üzeri ile oluşturulan Microsoft PowerPoint şablon sunumlarını temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS, PowerPoint Slayt Gösterisi, dosyalar Slayt Gösterisi amacıyla Microsoft PowerPoint kullanılarak oluşturulur. PPS dosyası okuma ve oluşturma, Microsoft PowerPoint 97-2003 tarafından desteklenir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | PPSM uzantılı dosyalar, Microsoft PowerPoint 2007 veya üstü ile oluşturulmuş Makro özellikli Slayt Gösterisi dosya biçimini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX, Power Point Slayt Gösterisi dosyası, Slayt Gösterisi amacıyla Microsoft PowerPoint 2007 ve üstü kullanılarak oluşturulur. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | PPT uzantılı bir dosya, SlideShow olarak görüntülemek için bir slayt koleksiyonundan oluşan PowerPoint dosyasını temsil eder. Microsoft PowerPoint 97-2003 tarafından kullanılan İkili Dosya Biçimini belirtir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | PPTM uzantılı dosyalar, Microsoft PowerPoint 2007 veya daha yüksek sürümlerle oluşturulan Makro etkin Sunum dosyalarıdır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | PPTX uzantılı dosyalar, popüler Microsoft PowerPoint uygulamasıyla oluşturulan sunum dosyalarıdır. İkili olan sunum dosyası biçimi PPT'nin önceki sürümünün aksine, PPTX biçimi Microsoft PowerPoint açık XML sunum dosyası biçimini temel alır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/presentation/pptx) . |

### Ayrıca bakınız

* class [FileType](../filetype)
* ad alanı [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* toplantı [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
