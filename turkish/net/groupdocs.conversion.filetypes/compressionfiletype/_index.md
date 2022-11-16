---
title: CompressionFileType
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: Sıkıştırma biçimlerini tanımlar. Aşağıdaki dosya türlerini içerir Zip./compressionfiletype/zip . Rar./compressionfiletype/rar . SevenZ./compressionfiletype/sevenz . Tar./compressionfiletype/tar . Gz./compressionfiletype/gz . Gzip./compressionfiletype/gzip . Bz2./compressionfiletype/bz2 . Sıkıştırma biçimleri hakkında daha fazla bilgi edininburadahttps//docs.fileformat.com/compression/ .
type: docs
weight: 810
url: /tr/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Sıkıştırma biçimlerini tanımlar. Aşağıdaki dosya türlerini içerir: [`Zip`](./zip) . [`Rar`](./rar) . [`SevenZ`](./sevenz) . [`Tar`](./tar) . [`Gz`](./gz) . [`Gzip`](./gzip) . [`Bz2`](./bz2) . Sıkıştırma biçimleri hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/compression/) .

```csharp
public sealed class CompressionFileType : FileType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [CompressionFileType](compressionfiletype)() | Serileştirme yapıcısı |

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
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | İki nesne örneğinin eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Varsayılan hash işlevi olarak işlev görür. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | Dizi gösterimi |

## Alanlar

| İsim | Tanım |
| --- | --- |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2, çoğunlukla UNIX veya Linux sisteminde BZIP2 açık kaynak sıkıştırma yöntemi kullanılarak oluşturulan sıkıştırılmış dosyalardır. Tek bir dosyanın sıkıştırılması için kullanılır ve birden fazla dosyanın arşivlenmesi için değildir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | .cab uzantılı bir dosya, sistem dosyaları kategorisine ait bir windows kabin dosyasına aittir. LZX, Quantum ve ZIP gibi sıkıştırılmış veri algoritmalarını destekleyen Microsoft Windows sürümlerinde arşiv dosyası biçiminde kaydedilen bir dosyadır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/system/cab/) . |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio, genel bir dosya arşivleme yardımcı programı ve bununla ilişkili dosya biçimidir. Öncelikle Unix benzeri bilgisayar işletim sistemlerine kurulur. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | Bir GZ dosyası, standart gzip (GNU zip) sıkıştırma algoritması kullanılarak oluşturulan sıkıştırılmış bir arşivdir. Birden çok sıkıştırılmış dosya, dizin ve dosya taslakları içerebilir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Bir Gzip dosyası, standart gzip (GNU zip) sıkıştırma algoritması kullanılarak oluşturulan sıkıştırılmış bir arşivdir. Birden çok sıkıştırılmış dosya, dizin ve dosya taslakları içerebilir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/compression/gz/) . |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | .lz uzantılı bir dosya, sıkıştırma için ücretsiz bir komut satırı aracı olan Lzip ile oluşturulan sıkıştırılmış bir arşiv dosyasıdır. Destek dosyalarını sıkıştırmak için birleştirmeyi destekler. LZ dosyalarının uygulama/lzip ortam türü vardır ve BZ2. 'den daha yüksek sıkıştırma oranlarını destekler. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/compression/bz2/) . |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | .lzma uzantılı bir dosya, LZMA (Lempel-Ziv-Markov zincir Algoritması) sıkıştırma yöntemi kullanılarak oluşturulan sıkıştırılmış bir arşiv dosyasıdır. Bunlar çoğunlukla Unix işletim sisteminde bulunur/kullanılır ve dosya boyutunu en aza indirmek için ZIP gibi diğer sıkıştırma algoritmalarına benzer. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/compression/lzma/) . |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | .rar uzantılı dosyalar, bilgilerin sıkıştırılmış veya normal biçimde saklanması için oluşturulmuş arşiv dosyalarıdır. Roshal ARchive dosya formatı anlamına gelen RAR. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/compression/rar/) . |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z, dosya ve klasörleri yüksek sıkıştırma oranıyla sıkıştırmak için kullanılan bir arşivleme biçimidir. Herhangi bir sıkıştırma ve şifreleme algoritmasının kullanılmasını mümkün kılan Açık Kaynak mimarisine dayalıdır. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/compression/7z/) . |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | .tar uzantılı dosyalar, bir veya daha fazla dosya toplamak için Unix tabanlı yardımcı programla oluşturulan arşivlerdir. Birden çok dosya, arşive dosya ve klasör ekleme desteğiyle sıkıştırılmamış bir biçimde saklanır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/compression/tar/) . |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ, LZMA2 sıkıştırma algoritmasını kullanan sıkıştırılmış bir dosya biçimidir. Popüler gzip ve bzip2 biçimlerinin yerine geçecek şekilde tasarlanmıştır ve bu eski standartlara göre çeşitli avantajlar sunar. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/compression/xz/) . |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | AZ dosyası, UNIX Sıkıştırılmış veri dosyalarına ait bir dosya kategorisidir. Sıkıştırılmış Unix dosyaları, Z dosyasının en popüler ve yaygın olarak kullanılan uzantı türüdür. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/compression/z/) . |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | .zip uzantılı bir dosya, bir veya daha fazla dosya veya dizini tutabilen bir arşivdir. ZIP dosya boyutunu azaltmak için arşive dahil edilen dosyalara sıkıştırma uygulanabilir. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/compression/zip/) . |

### Ayrıca bakınız

* class [FileType](../filetype)
* ad alanı [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* toplantı [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
