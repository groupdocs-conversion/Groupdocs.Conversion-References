---
title: ThreeDFileType
second_title: .NET API Başvurusu için GroupDocs.Conversion
description: 3B belgeleri tanımlar Aşağıdaki türleri içerir Fbx./threedfiletype/fbx 3D formatlar hakkında daha fazla bilgi edininburadahttps//wiki.fileformat.com/3d .
type: docs
weight: 940
url: /tr/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

3B belgeleri tanımlar Aşağıdaki türleri içerir: [`Fbx`](./fbx) 3D formatlar hakkında daha fazla bilgi edinin[burada](https://wiki.fileformat.com/3d) .

```csharp
public sealed class ThreeDFileType : FileType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | Serileştirme yapıcısı |

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
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | Bir AMF dosyası, Eklemeli Üretim süreçleri tarafından kullanılmak üzere nesne açıklamasına yönelik kılavuzlardan oluşur. Bir açılış XML etiketi içerir ve bir öğe ile biter. Bu, dosyanın XML sürümünü ve kodlamasını belirten bir XML bildirim satırından önce gelir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/3d/amf) . |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | .ase uzantılı bir dosya, sahne verilerini Autodesk kullanarak dışa aktarırken 2B veya 3B bilgileri içeren, bir sahnenin ASCII temsili olan bir Autodesk ASCII Scene Export dosya formatıdır. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/3d/ase) . |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | Bir DAE dosyası, etkileşimli 3B uygulamalar arasında veri alışverişi için kullanılan bir Dijital Varlık Değişimi dosya biçimidir. Bu dosya formatı, dijital varlıkların grafik yazılım uygulamaları arasında değiş tokuşu için açık standart bir XML şeması olan COLLADA (COLLAborative Design Activity) XML şemasına dayanmaktadır. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/3d/dae) . |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | .drc uzantılı bir dosya, Google Draco kitaplığı ile oluşturulmuş sıkıştırılmış bir 3D dosya biçimidir. Google, Draco'yu 3B geometrik ağları ve nokta bulutlarını sıkıştırmak ve sıkıştırmasını açmak için açık kaynak kitaplık olarak sunar ve 3B grafiklerin depolanmasını ve iletimini geliştirir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/3d/drc) . |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox, orijinal olarak Kaydara tarafından MotionBuilder için geliştirilmiş popüler bir 3D dosya formatıdır. 2006 yılında Autodesk Inc tarafından satın alındı ve şu anda birçok 3D aracı tarafından kullanılan ana 3D değişim formatlarından biri. FBX hem ikili hem de ASCII dosya biçiminde mevcuttur. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/3d/fbx) . |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (GL İletim Formatı), 3B model bilgilerini JSON formatında saklayan bir 3B dosya formatıdır. JSON kullanımı, hem 3B varlıkların boyutunu hem de bu varlıkları paketinden çıkarmak ve kullanmak için gereken çalışma zamanı işlemlerini en aza indirir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/3d/gltf) . |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jüpiter Mozaikleme), Siemens PLM Software tarafından geliştirilmiş verimli, endüstri odaklı ve esnek, ISO standartlaştırılmış bir 3D veri formatıdır. Havacılık, otomotiv endüstrisi ve Ağır Ekipmanların mekanik CAD alanları, en önde gelen 3D görselleştirme formatı olarak JT'yi kullanır. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/3d/jt) . |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | OBJ dosyaları, geometrik nesneleri tanımlamak ve saklamak için Wavefront'un Advanced Visualizer uygulaması tarafından kullanılır. Geometrik verilerin ileri ve geri iletimi OBJ dosyaları aracılığıyla mümkün olur. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/3d/obj) . |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, Çokgen Dosya Biçimi, çokgenler topluluğu olarak tanımlanan grafik nesneleri depolayan 3B dosya biçimini temsil eder. Bu dosya biçiminin amacı, çok çeşitli modeller için yararlı olacak kadar genel olan basit ve kolay bir dosya türü oluşturmaktı. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/3d/ply) . |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | RVM veri dosyaları, AVEVA PDMS ile ilgilidir. RVM dosyası, bir AVEVA Plant Design Management System Model proje dosyasıdır. AVEVA'nın Tesis Tasarım Yönetim Sistemi (PDMS), projeleri yönetmek için veri merkezli teknolojiyi kullanan en popüler 3B tasarım sistemidir. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/3d/rvm) . |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | .3ds uzantılı bir dosya, Autodesk 3D Studio tarafından kullanılan 3D Sudio (DOS) ağ dosyası biçimini temsil eder. Autodesk 3D Studio, 1990'lardan beri 3D dosya formatı pazarındadır ve şimdi 3D modelleme, animasyon ve işleme ile çalışmak için 3D Studio MAX'a dönüşmüştür. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/3d/3ds) . |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, 3B Üretim Formatı, uygulamalar tarafından 3B nesne modellerini çeşitli diğer uygulamalara, platformlara, hizmetlere ve yazıcılara işlemek için kullanılır. 3D yazıcıların en son sürümleriyle çalışmak için STL gibi diğer 3D dosya biçimlerindeki sınırlamalardan ve sorunlardan kaçınmak için oluşturulmuştur. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/3d/3mf) . |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Evrensel 3D), 3D bilgisayar grafikleri için sıkıştırılmış bir dosya formatı ve veri yapısıdır. Renk ve yapı ile üçgen kafesler, aydınlatma, gölgeleme, hareket verileri, çizgiler ve noktalar gibi 3D model bilgilerini içerir. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/3d/u3d) . |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | .usd uzantılı bir dosya, dijital içerik oluşturma uygulamaları arasında veri alışverişi ve artırma amacıyla verileri kodlayan bir Evrensel Sahne Tanımı dosya biçimidir. Pixar tarafından geliştirilen USD, temel varlıkları (modeller gibi) veya animasyonu değiştirme yeteneği sağlar. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/3d/usd) . |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | .usdz içeren bir dosya, arşive gömülü diğer biçimlerdeki (dokular ve animasyonlar gibi) dosyaları içeren ve bunlar için proxy'ler içeren USD (Evrensel Sahne Tanımı) dosya biçimi için sıkıştırılmamış ve şifrelenmemiş bir ZIP arşividir ve bunları doğrudan Paketi açmaya gerek kalmadan USD çalışma zamanı. Bu dosya formatı hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/3d/usdz) . |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | Sanal Gerçeklik Modelleme Dili (VRML), World Wide Web (www) üzerinde etkileşimli 3B dünya nesnelerinin temsili için bir dosya biçimidir. Kullanımını, illüstrasyonlar, tanım ve sanal gerçeklik sunumları gibi karmaşık sahnelerin üç boyutlu temsillerini oluştururken bulur. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/3d/vrml) . |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | .x uzantılı bir dosya, Microsoft DirectX 2.0 ile tanıtılan DirectX 3D Graphics eski dosya biçimini ifade eder. Oyunlarda 3B grafik oluşturma için kullanıldı ve kafesler, dokular, animasyonlar ve kullanıcı tanımlı nesneler için yapıları belirtir. Autodesk FBX dosya formatı daha modern bir format olarak daha iyi hizmet verdiği için 2014'ten beri kullanımdan kaldırılmıştır. Bu dosya biçimi hakkında daha fazla bilgi edinin[burada](https://docs.fileformat.com/3d/x) . |

### Ayrıca bakınız

* class [FileType](../filetype)
* ad alanı [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* toplantı [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
