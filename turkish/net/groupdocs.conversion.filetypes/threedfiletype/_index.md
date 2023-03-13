---
title: ThreeDFileType
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: 3B belgeleri tanımlar Aşağıdaki türleri içerir Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/x 3B biçimler hakkında daha fazla bilgi edininBuradahttps//wiki.fileformat.com/3d .
type: docs
weight: 1060
url: /tr/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

3B belgeleri tanımlar Aşağıdaki türleri içerir: [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x) 3B biçimler hakkında daha fazla bilgi edinin[Burada](https://wiki.fileformat.com/3d) .

```csharp
public sealed class ThreeDFileType : FileType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | Serileştirme oluşturucu |

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
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | Bir AMF dosyası, Eklemeli Üretim süreçlerinde kullanılmak üzere nesnelerin tanımına yönelik kılavuzlardan oluşur. Bir açılış XML etiketi içerir ve bir öğe ile biter. Bunun öncesinde, dosyanın XML sürümünü ve kodlamasını belirten bir XML bildirim satırı gelir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/3d/amf) . |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | .ase uzantılı bir dosya, sahne verilerini Autodesk kullanarak dışa aktarırken 2B veya 3B bilgiler içeren, bir sahnenin ASCII temsili olan bir Autodesk ASCII Sahne Dışa Aktarma dosya biçimidir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/3d/ase) . |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | DAE dosyası, etkileşimli 3B uygulamalar arasında veri alışverişi için kullanılan bir Dijital Varlık Değişimi dosya biçimidir. Bu dosya formatı, grafik yazılım uygulamaları arasında dijital varlıkların değiş tokuşu için açık standart bir XML şeması olan COLLADA (COLLAborative Design Activity) XML şemasına dayalıdır. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/3d/dae) . |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | .drc uzantılı bir dosya, Google Draco kitaplığı ile oluşturulan sıkıştırılmış bir 3B dosya biçimidir. Google, Draco'yu 3B geometrik ağları ve nokta bulutlarını sıkıştırmak ve açmak için açık kaynak kitaplığı olarak sunar ve 3B grafiklerin depolanmasını ve iletilmesini iyileştirir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/3d/drc) . |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox, orijinal olarak Kaydara tarafından MotionBuilder için geliştirilmiş popüler bir 3D dosya formatıdır. 2006 yılında Autodesk Inc tarafından satın alındı ve şu anda birçok 3B araç tarafından kullanılan ana 3B değişim biçimlerinden biri. FBX, hem ikili hem de ASCII dosya biçiminde mevcuttur. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/3d/fbx) . |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (GL İletim Biçimi), 3B model bilgilerini JSON biçiminde depolayan bir 3B dosya biçimidir. JSON kullanımı, hem 3B varlıkların boyutunu hem de bu varlıkları paketten çıkarmak ve kullanmak için gereken çalışma zamanı işlemeyi en aza indirir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/3d/gltf) . |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jüpiter Tessellation), Siemens PLM Software tarafından geliştirilen verimli, endüstri odaklı ve esnek, ISO standardize edilmiş bir 3D veri formatıdır. Havacılık, otomotiv endüstrisi ve Ağır Ekipman mekanik CAD alanları, JT'yi en önde gelen 3D görselleştirme formatı olarak kullanır. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/3d/jt) . |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | OBJ dosyaları, geometrik nesneleri tanımlamak ve depolamak için Wavefront'un Advanced Visualizer uygulaması tarafından kullanılır. Geometrik verilerin geriye ve ileriye iletimi OBJ dosyaları aracılığıyla mümkün olmaktadır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/3d/obj) . |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, Çokgen Dosya Biçimi, bir çokgen koleksiyonu olarak tanımlanan grafik nesneleri depolayan 3B dosya biçimini temsil eder. Bu dosya formatının amacı, geniş bir model yelpazesi için kullanışlı olacak kadar genel olan basit ve kolay bir dosya tipi oluşturmaktı. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/3d/ply) . |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | RVM veri dosyaları, AVEVA PDMS ile ilişkilidir. RVM dosyası, bir AVEVA Tesis Tasarım Yönetim Sistemi Modeli proje dosyasıdır. AVEVA'nın Tesis Tasarım Yönetim Sistemi (PDMS), projeleri yönetmek için veri merkezli teknolojiyi kullanan en popüler 3B tasarım sistemidir. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/3d/rvm) . |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | .3ds uzantılı bir dosya, Autodesk 3D Studio tarafından kullanılan 3D Ses (DOS) ağ dosyası formatını temsil eder. Autodesk 3D Studio, 1990'lardan beri 3D dosya formatı pazarında yer alıyor ve şimdi 3D modelleme, animasyon ve işleme ile çalışmak için 3D Studio MAX'a dönüştü. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/3d/3ds) . |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, 3B Üretim Formatı, uygulamalar tarafından 3B nesne modellerini çeşitli diğer uygulamalara, platformlara, hizmetlere ve yazıcılara dönüştürmek için kullanılır. 3B yazıcıların en son sürümleriyle çalışmak için STL gibi diğer 3B dosya biçimlerindeki sınırlamaları ve sorunları ortadan kaldırmak için oluşturulmuştur. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/3d/3mf) . |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D), 3D bilgisayar grafikleri için sıkıştırılmış bir dosya formatı ve veri yapısıdır. Üçgen kafesler, aydınlatma, gölgeleme, hareket verileri, çizgiler ve noktalar gibi renk ve yapıya sahip 3B model bilgilerini içerir. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/3d/u3d) . |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | .usd uzantılı bir dosya, dijital içerik oluşturma uygulamaları arasında veri alışverişi ve artırma amacıyla verileri kodlayan bir Evrensel Sahne Tanımı dosya biçimidir. Pixar tarafından geliştirilen USD, temel varlıkları (modeller gibi) veya animasyonu değiş tokuş etme yeteneği sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/3d/usd) . |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | .usdz içeren bir dosya, arşive katıştırılmış diğer biçimlerdeki (dokular ve animasyonlar gibi) dosyaları içeren ve bunlar için proxy'ler içeren ve bunları doğrudan Paketi açmaya gerek kalmadan USD çalışma zamanı. Bu dosya formatı hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/3d/usdz) . |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | Sanal Gerçeklik Modelleme Dili (VRML), World Wide Web (www) üzerinde etkileşimli 3B dünya nesnelerinin temsili için bir dosya biçimidir. Kullanımını, illüstrasyonlar, tanım ve sanal gerçeklik sunumları gibi karmaşık sahnelerin üç boyutlu temsillerini oluştururken bulur. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/3d/vrml) . |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | .x uzantılı bir dosya, Microsoft DirectX 2.0 ile tanıtılan DirectX 3D Graphics eski dosya biçimini ifade eder. Oyunlarda 3B grafik oluşturma için kullanıldı ve kafesler, dokular, animasyonlar ve kullanıcı tanımlı nesneler için yapıları belirtir. Autodesk FBX dosya formatı daha modern bir format olarak daha iyi hizmet verdiği için 2014'ten beri kullanımdan kaldırılmıştır. Bu dosya biçimi hakkında daha fazla bilgi edinin[Burada](https://docs.fileformat.com/3d/x) . |

### Ayrıca bakınız

* class [FileType](../filetype)
* ad alanı [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* toplantı [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
