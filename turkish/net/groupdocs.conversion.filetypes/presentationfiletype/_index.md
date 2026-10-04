---
title: "SunumDosyaTürü"
second_title: "GroupDocs.Conversion for .NET API Referansı"
description: "Sunum verilerini (slaytlar, şekiller, metin, animasyonlar, video, ses ve gömülü nesneler) barındırmak için kayıt koleksiyonunu depolayan Sunum dosya formatlarını tanımlar. Aşağıdaki dosya türlerini içerir Odp./presentationfiletype/odp Otp./presentationfiletype/otp Pot./presentationfiletype/pot Potm./presentationfiletype/potm Potx./presentationfiletype/potx Pps./presentationfiletype/pps Ppsm./presentationfiletype/ppsm Ppsx./presentationfiletype/ppsx Ppt./presentationfiletype/ppt Pptm./presentationfiletype/pptm Pptx./presentationfiletype/pptx. Sunum formatları hakkında daha fazla bilgi için burada https//wiki.fileformat.com/presentation."
type: docs
weight: 1210
url: /tr/net/groupdocs.conversion.filetypes/presentationfiletype/
---
## PresentationFileType class

Sunum verilerini (slaytlar, şekiller, metin, animasyonlar, video, ses ve gömülü nesneler) barındırmak için kayıt koleksiyonunu depolayan Sunum dosya formatlarını tanımlar. Aşağıdaki dosya türlerini içerir: [`Odp`](./odp), [`Otp`](./otp), [`Pot`](./pot), [`Potm`](./potm), [`Potx`](./potx), [`Pps`](./pps), [`Ppsm`](./ppsm), [`Ppsx`](./ppsx), [`Ppt`](./ppt), [`Pptm`](./pptm), [`Pptx`](./pptx). Sunum formatları hakkında daha fazla bilgi için [burada](https://wiki.fileformat.com/presentation).

```csharp
public sealed class PresentationFileType : FileType
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [PresentationFileType](presentationfiletype)() | Serileştirme yapıcısı |

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
| static readonly [Fodp](../../groupdocs.conversion.filetypes/presentationfiletype/fodp) | FODP uzantılı dosyalar OpenDocument Düz XML Sunumu temsil eder. Sunum dosyası OpenDocument formatında kaydedilir, ancak standart .ODP dosyalarında kullanılan .ZIP konteyneri yerine düz XML formatı kullanılarak kaydedilir. |
| static readonly [Odp](../../groupdocs.conversion.filetypes/presentationfiletype/odp) | ODP uzantılı dosyalar, OpenOffice.org tarafından OASISOpen standardında kullanılan sunum dosya formatını temsil eder. Bu dosya formatı hakkında daha fazla bilgi için [burada](https://wiki.fileformat.com/presentation/odp). |
| static readonly [Otp](../../groupdocs.conversion.filetypes/presentationfiletype/otp) | .OTP uzantılı dosyalar, OASIS OpenDocument standart formatında uygulamalar tarafından oluşturulan sunum şablonu dosyalarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi için [burada](https://wiki.fileformat.com/presentation/otp). |
| static readonly [Pot](../../groupdocs.conversion.filetypes/presentationfiletype/pot) | .POT uzantılı dosyalar, PowerPoint 97-2003 sürümleri tarafından oluşturulan Microsoft PowerPoint şablon dosyalarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi için [burada](https://wiki.fileformat.com/presentation/pot). |
| static readonly [Potm](../../groupdocs.conversion.filetypes/presentationfiletype/potm) | POTM uzantılı dosyalar, Makroları destekleyen Microsoft PowerPoint şablon dosyalarıdır. POTM dosyaları PowerPoint 2007 veya daha yeni sürümlerle oluşturulur ve daha fazla sunum dosyası oluşturmak için kullanılabilecek varsayılan ayarları içerir. Bu dosya formatı hakkında daha fazla bilgi için [burada](https://wiki.fileformat.com/presentation/potm). |
| static readonly [Potx](../../groupdocs.conversion.filetypes/presentationfiletype/potx) | .POTX uzantılı dosyalar, Microsoft PowerPoint 2007 ve üzeri sürümlerle oluşturulan Microsoft PowerPoint şablon sunumlarını temsil eder. Bu dosya formatı hakkında daha fazla bilgi için [burada](https://wiki.fileformat.com/presentation/potx). |
| static readonly [Pps](../../groupdocs.conversion.filetypes/presentationfiletype/pps) | PPS, PowerPoint Slayt Gösterisi, dosyaları, Slayt Gösterisi amacıyla Microsoft PowerPoint kullanılarak oluşturulur. PPS dosyasının okunması ve oluşturulması Microsoft PowerPoint 97-2003 tarafından desteklenir. Bu dosya formatı hakkında daha fazla bilgi için [burada](https://wiki.fileformat.com/presentation/pps). |
| static readonly [Ppsm](../../groupdocs.conversion.filetypes/presentationfiletype/ppsm) | PPSM uzantılı dosyalar, Microsoft PowerPoint 2007 veya daha yüksek sürümlerle oluşturulan Makro destekli Slayt Gösterisi dosya formatını temsil eder. Bu dosya formatı hakkında daha fazla bilgi için [burada](https://wiki.fileformat.com/presentation/ppsm). |
| static readonly [Ppsx](../../groupdocs.conversion.filetypes/presentationfiletype/ppsx) | PPSX, PowerPoint Slayt Gösterisi, dosyaları Microsoft PowerPoint 2007 ve üzeri sürümlerle Slayt Gösterisi amacıyla oluşturulur. Bu dosya formatı hakkında daha fazla bilgi için [burada](https://wiki.fileformat.com/presentation/ppsx). |
| static readonly [Ppt](../../groupdocs.conversion.filetypes/presentationfiletype/ppt) | PPT uzantılı bir dosya, Slayt Gösterisi olarak görüntülenmek üzere bir slayt koleksiyonundan oluşan PowerPoint dosyasını temsil eder. Bu, Microsoft PowerPoint 97-2003 tarafından kullanılan İkili Dosya Formatını belirtir. Bu dosya formatı hakkında daha fazla bilgi için [burada](https://wiki.fileformat.com/presentation/ppt). |
| static readonly [Pptm](../../groupdocs.conversion.filetypes/presentationfiletype/pptm) | PPTM uzantılı dosyalar, Microsoft PowerPoint 2007 veya daha yüksek sürümlerle oluşturulan Makro destekli Sunum dosyalarıdır. Bu dosya formatı hakkında daha fazla bilgi için [burada](https://wiki.fileformat.com/presentation/pptm). |
| static readonly [Pptx](../../groupdocs.conversion.filetypes/presentationfiletype/pptx) | PPTX uzantılı dosyalar, popüler Microsoft PowerPoint uygulamasıyla oluşturulan sunum dosyalarıdır. Önceki ikili PPT sunum dosyası formatının aksine, PPTX formatı Microsoft PowerPoint açık XML sunum dosyası formatına dayanır. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/presentation/pptx) bakın. |

### Ayrıca Bakınız

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
