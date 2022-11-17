---
title: DiagramFileType
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: Diyagram belgelerini tanımlar. Aşağıdaki türleri içerir Vdw./diagramfiletype/vdw  Vdx./diagramfiletype/vdx  Vsd./diagramfiletype/vsd  Vsdm./diagramfiletype/vsdm  Vsdx./diagramfiletype/vsdx  Vss./diagramfiletype/vss  Vssm./diagramfiletype/vssm  Vssx./diagramfiletype/vssx  Vst./diagramfiletype/vst  Vstm./diagramfiletype/vstm  Vstx./diagramfiletype/vstx  Vsx./diagramfiletype/vsx  Vtx./diagramfiletype/vtx .
type: docs
weight: 830
url: /tr/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Diyagram belgelerini tanımlar. Aşağıdaki türleri içerir: [`Vdw`](./vdw) , [`Vdx`](./vdx) , [`Vsd`](./vsd) , [`Vsdm`](./vsdm) , [`Vsdx`](./vsdx) , [`Vss`](./vss) , [`Vssm`](./vssm) , [`Vssx`](./vssx) , [`Vst`](./vst) , [`Vstm`](./vstm) , [`Vstx`](./vstx) , [`Vsx`](./vsx) , [`Vtx`](./vtx) .

```csharp
public sealed class DiagramFileType : FileType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | Serileştirme yapıcısı |

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
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW, bir Web çizimini işlemek için gereken akışları ve depoları belirten Visio Graphics Service dosya biçimidir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/web/vdw) . |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Microsoft Visio'da oluşturulan ancak XML biçiminde kaydedilen herhangi bir çizim veya grafik .VDX uzantısına sahiptir. Microsoft tarafından geliştirilen Visio yazılımında bir Visio çizim XML dosyası oluşturulur. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/vdx) . |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | VSD dosyaları, çeşitli grafik nesneleri ve bunlar arasındaki bağlantıyı temsil etmek için Microsoft Visio uygulamasıyla oluşturulan çizimlerdir. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/vsd) . |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | VSDM uzantılı dosyalar, makroları destekleyen Microsoft Visio uygulaması ile oluşturulmuş çizim dosyalarıdır. VSDM dosyaları, VSDX'e benzer OPC/XML çizimleridir, ancak dosya açıldığında makro çalıştırma özelliği de sağlar. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/vsdm) . |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | .VSDX uzantılı dosyalar, Microsoft Office 2013'ten itibaren tanıtılan Microsoft Visio dosya biçimini temsil eder. Microsoft Visio'nun önceki sürümleri tarafından desteklenen ikili dosya biçimi .VSD'nin yerini almak üzere geliştirilmiştir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/vsdx) . |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS, Microsoft Visio 2007 ve önceki sürümlerle oluşturulmuş şablon dosyalarıdır. Kalıp dosyaları, bir .VSD Visio çizimine dahil edilebilecek çizim nesneleri sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/vss) . |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | .VSSM uzantılı dosyalar, makro desteği sağlayan Microsoft Visio Stencil dosyalarıdır. Bir VSSM dosyası açıldığında, istenen biçimlendirmeyi ve şekillerin bir diyagramda yerleştirilmesini sağlamak için makroların çalıştırılmasına izin verir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/vssm) . |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | .VSSX uzantılı dosyalar, Microsoft Visio 2013 ve üstü ile oluşturulan çizim şablonlarıdır. VSSX dosya formatı, Visio 2013 ve üstü ile açılabilir. Visio dosyaları, şekiller koleksiyonu, bağlayıcılar, akış şemaları, ağ düzeni, UML diyagramları, gibi çeşitli çizim öğelerini temsil etmesiyle bilinir. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/vssx) . |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | VST uzantılı dosyalar, Microsoft Visio ile oluşturulan vektör görüntü dosyalarıdır ve daha fazla dosya oluşturmak için şablon görevi görür. Bu şablon dosyaları ikili dosya biçimindedir ve yeni Visio çizimlerinin oluşturulması için kullanılan varsayılan düzeni ve ayarları içerir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/vst) . |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | VSTM uzantılı dosyalar, makroları destekleyen Microsoft Visio ile oluşturulmuş şablon dosyalarıdır. VSDX dosyalarının aksine, VSTM şablonlarından oluşturulan dosyalar, Visual Basic for Applications (VBA) kodunda geliştirilen makroları çalıştırabilir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/vstm) . |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | VSTX uzantılı dosyalar, Microsoft Visio 2013 ve üzeri ile oluşturulmuş çizim şablon dosyalarıdır. Bu VSTX dosyaları, varsayılan düzen ve ayarlarla .VSDX dosyaları olarak kaydedilen Visio çizimleri oluşturmak için başlangıç noktası sağlar. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/vstx) . |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | .VSX uzantılı dosyalar, Microsoft Visio'da diyagram oluşturmak için kullanılan çizimlerden ve şekillerden oluşan kalıpları ifade eder. VSX dosyaları XML dosya biçiminde kaydedilir ve Visio 2013'e kadar desteklenirdi. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/vsx) . |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | VTX uzantılı bir dosya, XML dosya biçiminde diske kaydedilen bir Microsoft Visio çizim şablonudur. Şablon, aynı ayarlara sahip birden çok Visio dosyası oluşturmak için kullanılabilecek temel ayarlara sahip bir dosya sağlamayı amaçlamaktadır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/image/vtx) . |

### Ayrıca bakınız

* class [FileType](../filetype)
* ad alanı [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* toplantı [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
