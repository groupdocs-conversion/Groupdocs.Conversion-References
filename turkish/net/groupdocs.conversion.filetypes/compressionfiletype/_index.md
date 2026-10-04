---
title: "CompressionFileType"
second_title: "GroupDocs.Conversion for .NET API Referansı"
description: "Sıkıştırma formatlarını tanımlar. Aşağıdaki dosya türlerini içerir Zip./compressionfiletype/zip. Rar./compressionfiletype/rar. SevenZ./compressionfiletype/sevenz. Tar./compressionfiletype/tar. Gz./compressionfiletype/gz. Gzip./compressionfiletype/gzip. Bz2./compressionfiletype/bz2. Lz./compressionfiletype/lz. Z./compressionfiletype/z. Xz./compressionfiletype/xz. Xz./compressionfiletype/xz. Cpio./compressionfiletype/cpio. Cab./compressionfiletype/cab. Lzma./compressionfiletype/lzma. Zst./compressionfiletype/zst. Uue./compressionfiletype/uue. Lha./compressionfiletype/lha. Lz4./compressionfiletype/lz4. Xar./compressionfiletype/xar. Wim./compressionfiletype/wim. Aar./compressionfiletype/aar. Alz./compressionfiletype/alz. Sıkıştırma formatları hakkında daha fazla bilgi için buraya https//docs.fileformat.com/compression/."
type: docs
weight: 1080
url: /tr/net/groupdocs.conversion.filetypes/compressionfiletype/
---
## CompressionFileType class

Sıkıştırma formatlarını tanımlar. Aşağıdaki dosya türlerini içerir: [`Zip`](./zip). [`Rar`](./rar). [`SevenZ`](./sevenz). [`Tar`](./tar). [`Gz`](./gz). [`Gzip`](./gzip). [`Bz2`](./bz2). [`Lz`](./lz). [`Z`](./z). [`Xz`](./xz). [`Xz`](./xz). [`Cpio`](./cpio). [`Cab`](./cab). [`Lzma`](./lzma). [`Zst`](./zst). [`Uue`](./uue). [`Lha`](./lha). [`Lz4`](./lz4). [`Xar`](./xar). [`Wim`](./wim). [`Aar`](./aar). [`Alz`](./alz). Sıkıştırma formatları hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/compression/) tıklayın.

```csharp
public sealed class CompressionFileType : FileType
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | Dosya türü açıklaması |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | Dosya uzantısı |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | Dosya ailesi |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | Dosya formatı |
| [IsMultiFileArchive](../../groupdocs.conversion.filetypes/compressionfiletype/ismultifilearchive) { get; } | Formatın tek bir arşivde birden fazla dosya/klasör destekleyip desteklemediğini tanımlar. |

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
| static readonly [Aar](../../groupdocs.conversion.filetypes/compressionfiletype/aar) | .aar uzantılı bir dosya, Apple'ın macOS ile birlikte sunduğu ve dosya ve klasörleri gruplamak için kullanılan bir Apple Arşivi'dir. Her bir giriş kendi başına sıkıştırılır, genellikle LZFSE ile. |
| static readonly [Alz](../../groupdocs.conversion.filetypes/compressionfiletype/alz) | .alz uzantılı bir dosya, Güney Kore'de yaygın olarak kullanılan ESTsoft'a ait bir ALZip arşividir. Girişler ayrı ayrı şifrelenebilir. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/compression/alz/) tıklayın. |
| static readonly [Bz2](../../groupdocs.conversion.filetypes/compressionfiletype/bz2) | BZ2, BZIP2 açık kaynak sıkıştırma yöntemi kullanılarak, çoğunlukla UNIX veya Linux sistemlerinde oluşturulan sıkıştırılmış dosyalardır. Tek bir dosyanın sıkıştırılması için kullanılır ve birden fazla dosyanın arşivlenmesi amacıyla değildir. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/compression/bz2/) tıklayın. |
| static readonly [Cab](../../groupdocs.conversion.filetypes/compressionfiletype/cab) | .cab uzantılı bir dosya, sistem dosyaları kategorisine ait bir Windows kabin dosyasıdır. LZX, Quantum ve ZIP gibi sıkıştırılmış veri algoritmalarını destekleyen Microsoft Windows sürümlerinde arşiv dosyası formatı olarak kaydedilir. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/system/cab/) tıklayın. |
| static readonly [Cpio](../../groupdocs.conversion.filetypes/compressionfiletype/cpio) | Cpio, genel bir dosya arşivleme yardımcı programı ve ilişkili dosya formatıdır. Çoğunlukla Unix benzeri bilgisayar işletim sistemlerine kurulur. |
| static readonly [Gz](../../groupdocs.conversion.filetypes/compressionfiletype/gz) | GZ dosyası, standart gzip (GNU zip) sıkıştırma algoritması kullanılarak oluşturulan sıkıştırılmış bir arşivdir. Birden fazla sıkıştırılmış dosya, dizin ve dosya taslağı içerebilir. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/compression/gz/) tıklayın. |
| static readonly [Gzip](../../groupdocs.conversion.filetypes/compressionfiletype/gzip) | Gzip dosyası, standart gzip (GNU zip) sıkıştırma algoritması kullanılarak oluşturulan sıkıştırılmış bir arşivdir. Birden fazla sıkıştırılmış dosya, dizin ve dosya taslağı içerebilir. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/compression/gz/) tıklayın. |
| static readonly [Iso](../../groupdocs.conversion.filetypes/compressionfiletype/iso) | .iso uzantılı bir dosya, CD veya DVD gibi bir optik diskteki tüm verinin içeriğini temsil eden sıkıştırılmamış arşiv disk görüntüsü dosyasıdır. ISO-9660 standardına dayanarak, ISO görüntü dosya formatı diskin verilerini ve içinde depolanan dosya sistemi bilgilerini içerir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/compression/iso/). |
| static readonly [Lha](../../groupdocs.conversion.filetypes/compressionfiletype/lha) | .lzh ve .lha uzantılı bir dosya genellikle arşiv sıkıştırma dosya formatına ilişkindir. Bu dosya formatı ZIP, RAR vb. gibi diğer dosya sıkıştırma formatlarıyla aynıdır. Bu formatların temel amacı, dosyaları kolayca gönderebilmek ve sıkıştırılmış biçimde bir arada tutabilmek için boyutlarını küçültmektir. |
| static readonly [Lz](../../groupdocs.conversion.filetypes/compressionfiletype/lz) | .lz uzantılı bir dosya, sıkıştırma için ücretsiz bir komut satırı aracı olan Lzip ile oluşturulmuş sıkıştırılmış arşiv dosyasıdır. Destek dosyalarını sıkıştırmak için birleştirmeyi destekler. LZ dosyalarının medya türü application/lzip'tir ve BZ2'ye göre daha yüksek sıkıştırma oranları sunar. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/compression/bz2/). |
| static readonly [Lz4](../../groupdocs.conversion.filetypes/compressionfiletype/lz4) | .lz4 uzantılı bir dosya, LZ4 sıkıştırmasını destekleyen uygulama/araçlarla oluşturulmuş sıkıştırılmış arşiv dosyasıdır. LZ4 algoritması, hız ile sıkıştırma oranı arasındaki dengeye odaklanır. Sıkıştırılmış LZ4 arşivleri, LZ4 komut satırı aracıyla oluşturulabilir ve aynı araçla açılabilir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/compression/lz4/). |
| static readonly [Lzma](../../groupdocs.conversion.filetypes/compressionfiletype/lzma) | .lzma uzantılı bir dosya, LZMA (Lempel-Ziv-Markov zinciri Algoritması) sıkıştırma yöntemiyle oluşturulmuş sıkıştırılmış arşiv dosyasıdır. Bu dosyalar çoğunlukla Unix işletim sisteminde bulunur/kullanılır ve dosya boyutunu küçültmek için ZIP gibi diğer sıkıştırma algoritmalarına benzer. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/compression/lzma/). |
| static readonly [Rar](../../groupdocs.conversion.filetypes/compressionfiletype/rar) | .rar uzantılı dosyalar, bilgiyi sıkıştırılmış veya normal biçimde depolamak için oluşturulan arşiv dosyalarıdır. RAR, Roshal ARchive dosya formatının kısaltmasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/compression/rar/). |
| static readonly [SevenZ](../../groupdocs.conversion.filetypes/compressionfiletype/sevenz) | 7z, dosya ve klasörleri yüksek sıkıştırma oranıyla sıkıştırmak için kullanılan bir arşivleme formatıdır. Açık Kaynak mimarisine dayanır ve bu sayede herhangi bir sıkıştırma ve şifreleme algoritması kullanılabilir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/compression/7z/). |
| static readonly [Tar](../../groupdocs.conversion.filetypes/compressionfiletype/tar) | .tar uzantılı dosyalar, bir veya daha fazla dosyayı toplamak için Unix tabanlı bir yardımcı programla oluşturulan arşivlerdir. Birden çok dosya, dosya ve klasör ekleme desteğiyle sıkıştırılmamış bir formatta depolanır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/compression/tar/). |
| static readonly [Uue](../../groupdocs.conversion.filetypes/compressionfiletype/uue) | Uuencoded arşiv, Unix-to-Unix kodlama şeması (uuencode) kullanılarak kodlanmış bir dosya veya dosya koleksiyonudur. Bu kodlama yöntemi ikili verileri metin formatına dönüştürür, bu da e-posta gibi yalnızca metni destekleyen kanallar üzerinden dosya göndermeyi kolaylaştırır. |
| static readonly [Wim](../../groupdocs.conversion.filetypes/compressionfiletype/wim) | .wim uzantılı bir dosya, Microsoft'un Windows dağıtımında kullandığı dosya tabanlı bir disk görüntüsü olan Windows Imaging Format arşividir. Tek bir arşiv bir veya daha fazla görüntüyü tutar ve her dosyayı, kaç görüntü referans gösterirse göstersin, yalnızca bir kez depolar. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/disc-and-media/wim/). |
| static readonly [Xar](../../groupdocs.conversion.filetypes/compressionfiletype/xar) | .xar uzantılı bir dosya, sıkıştırılmış XML olarak depolanan bir içerik tablosu etrafında inşa edilen bir eXtensible ARchive (genişletilebilir arşiv) formatıdır. macOS kurulum paketlerini dağıtmak için kullanılır ve her giriş kendi başına sıkıştırılmış olarak tutulur. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/compression/xar/). |
| static readonly [Xz](../../groupdocs.conversion.filetypes/compressionfiletype/xz) | XZ, LZMA2 sıkıştırma algoritmasını kullanan bir sıkıştırılmış dosya formatıdır. Popüler gzip ve bzip2 formatlarının yerine geçecek şekilde tasarlanmış olup, bu eski standartlara göre bir dizi avantaj sunar. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/compression/xz/). |
| static readonly [Z](../../groupdocs.conversion.filetypes/compressionfiletype/z) | Z dosyası, UNIX Sıkıştırılmış veri dosyalarına ait bir dosya kategorisidir. Sıkıştırılmış Unix dosyaları, Z dosyasının en popüler ve yaygın kullanılan uzantı türüdür. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/compression/z/). |
| static readonly [Zip](../../groupdocs.conversion.filetypes/compressionfiletype/zip) | .zip uzantılı bir dosya, bir veya daha fazla dosya ya da dizin içerebilen bir arşivdir. Arşiv, ZIP dosya boyutunu azaltmak için içindeki dosyalara sıkıştırma uygulanabilir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/compression/zip/). |
| static readonly [Zst](../../groupdocs.conversion.filetypes/compressionfiletype/zst) | ZST dosyası, Zstandard (zstd) sıkıştırma algoritmasıyla oluşturulan bir sıkıştırılmış dosyadır. Algoritma tarafından kayıpsız sıkıştırma ile yaratılan bir sıkıştırılmış dosyadır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/compression/zst/). |

### Ayrıca Bakınız

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
