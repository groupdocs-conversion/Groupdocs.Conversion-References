---
title: "DiagramFileType"
second_title: "GroupDocs.Conversion for .NET API Referansı"
description: "Diagram belgelerini tanımlar. Aşağıdaki türleri içerir Drawio./diagramfiletype/drawio Mmd./diagramfiletype/mmd Vdw./diagramfiletype/vdw Vdx./diagramfiletype/vdx Vsd./diagramfiletype/vsd Vsdm./diagramfiletype/vsdm Vsdx./diagramfiletype/vsdx Vss./diagramfiletype/vss Vssm./diagramfiletype/vssm Vssx./diagramfiletype/vssx Vst./diagramfiletype/vst Vstm./diagramfiletype/vstm Vstx./diagramfiletype/vstx Vsx./diagramfiletype/vsx Vtx./diagramfiletype/vtx."
type: docs
weight: 1100
url: /tr/net/groupdocs.conversion.filetypes/diagramfiletype/
---
## DiagramFileType class

Diagram belgelerini tanımlar. Aşağıdaki türleri içerir: [`Drawio`](./drawio), [`Mmd`](./mmd), [`Vdw`](./vdw), [`Vdx`](./vdx), [`Vsd`](./vsd), [`Vsdm`](./vsdm), [`Vsdx`](./vsdx), [`Vss`](./vss), [`Vssm`](./vssm), [`Vssx`](./vssx), [`Vst`](./vst), [`Vstm`](./vstm), [`Vstx`](./vstx), [`Vsx`](./vsx), [`Vtx`](./vtx).

```csharp
public sealed class DiagramFileType : FileType
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [DiagramFileType](diagramfiletype)() | Serileştirme yapıcısı |

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
| static readonly [Drawio](../../groupdocs.conversion.filetypes/diagramfiletype/drawio) | DRAWIO uzantılı bir dosya, diagrams.net (eski adıyla draw.io) ile oluşturulan bir diyagramdır. mxfile kök öğesiyle XML dosya formatında saklanır ve metin, görüntüler, düzen, şekiller ve konumlandırma gibi diyagram öğelerinin içeriğini ve biçimlendirmesini tutar. Bu dosya formatı hakkında daha fazla bilgi için [burada](https://wiki.fileformat.com/web/drawio) . |
| static readonly [Mmd](../../groupdocs.conversion.filetypes/diagramfiletype/mmd) | MMD uzantılı bir dosya, Mermaid işaretleme diliyle yazılmış bir diyagramdır. Akış şeması veya sequenceDiagram gibi diyagram deklarasyonu ile başlayan ve ardından düğümlerin ve aralarındaki bağlantıların tanımlandığı düz metin belge olarak saklanır. Bu dosya formatı hakkında daha fazla bilgi için [burada](https://mermaid.js.org/intro/) . |
| static readonly [Vdw](../../groupdocs.conversion.filetypes/diagramfiletype/vdw) | VDW, bir Web çizimini renderlemek için gereken akışları ve depolamaları belirten Visio Graphics Service dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi için [burada](https://wiki.fileformat.com/web/vdw) . |
| static readonly [Vdx](../../groupdocs.conversion.filetypes/diagramfiletype/vdx) | Microsoft Visio'da oluşturulan ancak XML formatında kaydedilen tüm çizimler veya grafikler .VDX uzantısına sahiptir. Visio yazılımı tarafından oluşturulan bir Visio çizimi XML dosyasıdır; bu yazılım Microsoft tarafından geliştirilmiştir. Bu dosya formatı hakkında daha fazla bilgi için [burada](https://wiki.fileformat.com/image/vdx) . |
| static readonly [Vsd](../../groupdocs.conversion.filetypes/diagramfiletype/vsd) | VSD dosyaları, Microsoft Visio uygulamasıyla oluşturulan ve çeşitli grafik nesneleri ile bunların birbirleriyle bağlantılarını temsil eden çizimlerdir. Bu dosya formatı hakkında daha fazla bilgi için [burada](https://wiki.fileformat.com/image/vsd) . |
| static readonly [Vsdm](../../groupdocs.conversion.filetypes/diagramfiletype/vsdm) | VSDM uzantılı dosyalar, makroları destekleyen Microsoft Visio uygulamasıyla oluşturulan çizim dosyalarıdır. VSDM dosyaları, VSDX'e benzer OPC/XML çizimleridir, ancak dosya açıldığında makroların çalıştırılmasını da sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vsdm). |
| static readonly [Vsdx](../../groupdocs.conversion.filetypes/diagramfiletype/vsdx) | .VSDX uzantılı dosyalar, Microsoft Office 2013'ten itibaren tanıtılan Microsoft Visio dosya formatını temsil eder. Daha eski Microsoft Visio sürümlerinin desteklediği ikili dosya formatı .VSD'nin yerini alması için geliştirilmiştir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vsdx). |
| static readonly [Vss](../../groupdocs.conversion.filetypes/diagramfiletype/vss) | VSS, Microsoft Visio 2007 ve öncesiyle oluşturulan şablon dosyalarıdır. Şablon dosyaları, bir .VSD Visio çizimine eklenebilen çizim nesneleri sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vss). |
| static readonly [Vssm](../../groupdocs.conversion.filetypes/diagramfiletype/vssm) | .VSSM uzantılı dosyalar, makroları destekleyen Microsoft Visio Şablon dosyalarıdır. Bir VSSM dosyası açıldığında, diyagramdaki şekillerin istenen biçimlendirilmesi ve yerleştirilmesi için makroların çalıştırılmasına izin verir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vssm). |
| static readonly [Vssx](../../groupdocs.conversion.filetypes/diagramfiletype/vssx) | .VSSX uzantılı dosyalar, Microsoft Visio 2013 ve üzeriyle oluşturulan çizim şablonlarıdır. VSSX dosya formatı Visio 2013 ve üzeriyle açılabilir. Visio dosyaları, şekil koleksiyonları, bağlayıcılar, akış şemaları, ağ düzeni, UML diyagramları gibi çeşitli çizim öğelerinin temsiliyle bilinir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vssx). |
| static readonly [Vst](../../groupdocs.conversion.filetypes/diagramfiletype/vst) | VST uzantılı dosyalar, Microsoft Visio ile oluşturulan vektör görüntü dosyalarıdır ve sonraki dosyaları oluşturmak için şablon görevi görür. Bu şablon dosyaları ikili dosya formatındadır ve yeni Visio çizimleri oluşturmak için kullanılan varsayılan düzen ve ayarları içerir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vst). |
| static readonly [Vstm](../../groupdocs.conversion.filetypes/diagramfiletype/vstm) | VSTM uzantılı dosyalar, makroları destekleyen Microsoft Visio ile oluşturulan şablon dosyalarıdır. VSDX dosyalarından farklı olarak, VSTM şablonlarından oluşturulan dosyalar Visual Basic for Applications (VBA) kodunda geliştirilen makroları çalıştırabilir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vstm). |
| static readonly [Vstx](../../groupdocs.conversion.filetypes/diagramfiletype/vstx) | VSTX uzantılı dosyalar, Microsoft Visio 2013 ve üzeriyle oluşturulan çizim şablon dosyalarıdır. Bu VSTX dosyaları, .VSDX dosyaları olarak kaydedilen Visio çizimleri oluşturmak için varsayılan düzen ve ayarlarla bir başlangıç noktası sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vstx). |
| static readonly [Vsx](../../groupdocs.conversion.filetypes/diagramfiletype/vsx) | .VSX uzantılı dosyalar, Microsoft Visio'da diyagram oluşturmak için kullanılan çizimler ve şekillerden oluşan şablonları ifade eder. VSX dosyaları XML dosya formatında kaydedilir ve Visio 2013'e kadar desteklenmiştir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vsx). |
| static readonly [Vtx](../../groupdocs.conversion.filetypes/diagramfiletype/vtx) | VTX uzantılı dosya, XML dosya formatında diske kaydedilen bir Microsoft Visio çizim şablonudur. Şablon, aynı ayarlara sahip birden fazla Visio dosyası oluşturmak için kullanılabilecek temel ayarları içeren bir dosya sağlamayı amaçlar. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/image/vtx). |

### Ayrıca Bakınız

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
