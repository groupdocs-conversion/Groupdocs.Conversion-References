---
title: CadFileType
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: 3B grafik dosya biçimleri için kullanılan ve 2B veya 3B tasarımlar içerebilen CAD belgelerini Bilgisayar Destekli Tasarım tanımlar. Aşağıdaki türleri içerir Dgn./cadfiletype/dgn  Dwf./cadfiletype/dwf  Dwg./cadfiletype/dwg  Dwt./cadfiletype/dwt  Dxf./cadfiletype/dxf  Ifc./cadfiletype/ifc  Igs./cadfiletype/igs  Plt./cadfiletype/plt  Stl./cadfiletype/stl . CAD biçimleri hakkında daha fazla bilgi edininburadahttps//wiki.fileformat.com/cad .
type: docs
weight: 800
url: /tr/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

3B grafik dosya biçimleri için kullanılan ve 2B veya 3B tasarımlar içerebilen CAD belgelerini (Bilgisayar Destekli Tasarım) tanımlar. Aşağıdaki türleri içerir: [`Dgn`](./dgn) , [`Dwf`](./dwf) , [`Dwg`](./dwg) , [`Dwt`](./dwt) , [`Dxf`](./dxf) , [`Ifc`](./ifc) , [`Igs`](./igs) , [`Plt`](./plt) , [`Stl`](./stl) . CAD biçimleri hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/cad) .

```csharp
public sealed class CadFileType : FileType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [CadFileType](cadfiletype)() | Serileştirme yapıcısı |

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
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | Ortak Dosya Formatı Dosyası. 3B paket tasarımları veya diğer model verilerini içeren CAD dosyası; kalıp kesme cihazı gibi bir CAD/CAM makinesi tarafından işlenebilir ve kesilebilir. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | DGN, Tasarım, dosyalar MicroStation ve Intergraph Etkileşimli Grafik Tasarım Sistemi gibi CAD uygulamaları tarafından oluşturulan ve desteklenen çizimlerdir. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/cad/dgn) . |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Tasarım Web Formatı (DWF), tasarım dosyalarının görüntülenmesi, gözden geçirilmesi veya yazdırılması için sıkıştırılmış formatta 2B/3B çizimi temsil eder. Tasarım verilerinin bir parçası olarak grafik ve metin içerir ve sıkıştırılmış biçimi nedeniyle dosyanın boyutunu azaltır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/cad/dwf) . |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | DWFX dosyası, Autodesk CAD yazılımı ile oluşturulan bir 2B veya 3B çizimdir. . DWF dosyası, ancak Microsoft'un XML Kağıt Spesifikasyonu (XPS) kullanılarak formatlanmıştır. |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | DWG uzantılı dosyalar, 2B ve 3B tasarım verilerini içermek için kullanılan tescilli ikili dosyaları temsil eder. ASCII dosyaları olan DXF gibi, DWG de CAD (Bilgisayar Destekli Tasarım) çizimleri için ikili dosya biçimini temsil eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/cad/dwg) . |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | DWT dosyası, DWG dosyaları olarak kaydedilebilen çizimler oluşturmak için başlangıç olarak kullanılan bir AutoCAD çizim şablon dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/cad/dwt) . |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF, Çizim Değişim Formatı veya Çizim Değişim Formatı, AutoCAD çizim dosyasının etiketli bir veri temsilidir. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/cad/dxf) . |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | IFC uzantılı dosyalar, yapı nesnelerini ve bunların özelliklerini içe ve dışa aktarmak için uluslararası standartları belirleyen Industry Foundation Classes (IFC) dosya biçimini ifade eder. Bu dosya biçimi, farklı yazılım uygulamaları arasında birlikte çalışabilirlik sağlar. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/cad/ifc) . |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Igs belge formatı |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | PLT dosya biçimi, Autodesk, Inc. tarafından sunulan vektör tabanlı bir çizici dosyasıdır ve belirli bir CAD dosyası için bilgi içerir. Çizim ayrıntıları, üretimde doğruluk ve kesinlik gerektirir ve tüm görüntüler noktalar yerine çizgiler kullanılarak yazdırıldığı için PLT dosyasının kullanılması bunu garanti eder. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/cad/plt) . |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL, stereolitrografinin kısaltması, 3 boyutlu yüzey geometrisini temsil eden değiştirilebilir bir dosya formatıdır. Dosya formatı, hızlı prototip oluşturma, 3D baskı ve bilgisayar destekli üretim gibi çeşitli alanlarda kullanım alanı bulur. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/cad/stl) . |

### Ayrıca bakınız

* class [FileType](../filetype)
* ad alanı [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* toplantı [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
