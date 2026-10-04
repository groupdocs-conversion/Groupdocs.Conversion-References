---
title: "ThreeDFileType"
second_title: "GroupDocs.Conversion for .NET API Referansı"
description: "3D belgeleri tanımlar Aşağıdaki türleri içerir Fbx./threedfiletype/fbxThreeDS./threedfiletype/threedsThreeMF./threedfiletype/threemfAmf./threedfiletype/amfAse./threedfiletype/aseRvm./threedfiletype/rvmDae./threedfiletype/daeDrc./threedfiletype/drcGltf./threedfiletype/gltfObj./threedfiletype/objPly./threedfiletype/plyJt./threedfiletype/jtU3d./threedfiletype/u3dUsd./threedfiletype/usdUsdz./threedfiletype/usdzVrml./threedfiletype/vrmlX./threedfiletype/xGlb./threedfiletype/glbMa./threedfiletype/maMb./threedfiletype/mb 3D formatları hakkında daha fazla bilgi için burayahttps//wiki.fileformat.com/3d."
type: docs
weight: 1250
url: /tr/net/groupdocs.conversion.filetypes/threedfiletype/
---
## ThreeDFileType class

3D belgeleri tanımlar Aşağıdaki türleri içerir: [`Fbx`](./fbx)[`ThreeDS`](./threeds)[`ThreeMF`](./threemf)[`Amf`](./amf)[`Ase`](./ase)[`Rvm`](./rvm)[`Dae`](./dae)[`Drc`](./drc)[`Gltf`](./gltf)[`Obj`](./obj)[`Ply`](./ply)[`Jt`](./jt)[`U3d`](./u3d)[`Usd`](./usd)[`Usdz`](./usdz)[`Vrml`](./vrml)[`X`](./x)[`Glb`](./glb)[`Ma`](./ma)[`Mb`](./mb) 3D formatları hakkında daha fazla bilgi için [buraya](https://wiki.fileformat.com/3d).

```csharp
public sealed class ThreeDFileType : FileType
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [ThreeDFileType](threedfiletype)() | Serileştirme yapıcısı |

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
| static readonly [Amf](../../groupdocs.conversion.filetypes/threedfiletype/amf) | Bir AMF dosyası, Katmanlı Üretim süreçleri tarafından kullanılmak üzere nesne açıklamaları için yönergeler içerir. Bir açılış XML etiketi içerir ve bir öğe ile sona erer. Bu, dosyanın XML sürümünü ve kodlamasını belirten bir XML deklarasyon satırı ile başlar. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/3d/amf). |
| static readonly [Ase](../../groupdocs.conversion.filetypes/threedfiletype/ase) | .ase uzantılı bir dosya, Autodesk ASCII Scene Export dosya formatıdır ve bir sahnenin ASCII temsili olup, Autodesk kullanarak sahne verilerini dışa aktarırken 2D veya 3D bilgileri içerir. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/3d/ase). |
| static readonly [Dae](../../groupdocs.conversion.filetypes/threedfiletype/dae) | DAE dosyası, etkileşimli 3D uygulamalar arasında veri alışverişi için kullanılan bir Digital Asset Exchange dosya formatıdır. Bu dosya formatı, grafik yazılım uygulamaları arasında dijital varlıkların değişimi için açık bir standart XML şeması olan COLLADA (COLLAborative Design Activity) XML şemasına dayanır. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/3d/dae). |
| static readonly [Drc](../../groupdocs.conversion.filetypes/threedfiletype/drc) | .drc uzantılı bir dosya, Google Draco kütüphanesi ile oluşturulmuş sıkıştırılmış bir 3D dosya formatıdır. Google, 3D geometrik ağları ve nokta bulutlarını sıkıştırmak ve açmak için açık kaynaklı bir kütüphane olan Draco'yu sunar ve 3D grafiklerin depolanmasını ve iletimini iyileştirir. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/3d/drc). |
| static readonly [Fbx](../../groupdocs.conversion.filetypes/threedfiletype/fbx) | FBX, FilmBox, orijinal olarak Kaydara tarafından MotionBuilder için geliştirilen popüler bir 3D dosya formatıdır. 2006'da Autodesk Inc tarafından satın alındı ve şimdi birçok 3D aracın kullandığı temel 3D değişim formatlarından biridir. FBX, hem ikili hem de ASCII dosya formatında mevcuttur. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/3d/fbx). |
| static readonly [Glb](../../groupdocs.conversion.filetypes/threedfiletype/glb) | GLB, GL Transmission Format (glTF) içinde kaydedilen 3D modellerin ikili dosya formatı temsilidir. Bu ikili format, glTF varlığını (JSON, .bin ve görüntüler) ikili bir blokta depolar. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/3d/glb). |
| static readonly [Gltf](../../groupdocs.conversion.filetypes/threedfiletype/gltf) | glTF (GL Transmission Format), 3D model bilgilerini JSON formatında depolayan bir 3D dosya formatıdır. JSON kullanımı, 3D varlıkların boyutunu ve bu varlıkları açmak ve kullanmak için gereken çalışma zamanı işleme süresini azaltır. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/3d/gltf). |
| static readonly [Jt](../../groupdocs.conversion.filetypes/threedfiletype/jt) | JT (Jupiter Tessellation), Siemens PLM Software tarafından geliştirilen verimli, endüstri odaklı ve esnek bir ISO standardına sahip 3D veri formatıdır. Havacılık, otomotiv endüstrisi ve Ağır Ekipman gibi Mekanik CAD alanları, JT'yi en önde gelen 3D görselleştirme formatı olarak kullanır. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/3d/jt). |
| static readonly [Ma](../../groupdocs.conversion.filetypes/threedfiletype/ma) | .ma uzantılı bir dosya, Autodesk Maya uygulamasıyla oluşturulan bir 3D proje dosyasıdır. Dosya hakkında bilgi belirtmek için büyük bir metin komut listesi içerir. Bu dosya formatı hakkında daha fazla bilgi için [buraya](https://docs.fileformat.com/3d/ma). |
| static readonly [Mb](../../groupdocs.conversion.filetypes/threedfiletype/mb) | .mb uzantılı bir dosya, Autodesk Maya uygulamasıyla oluşturulan ikili proje dosyasıdır. ASCII dosya formatında olan MA dosya formatının aksine, MB dosyaları ikili dosya formatında depolanır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/3d/mb). |
| static readonly [Obj](../../groupdocs.conversion.filetypes/threedfiletype/obj) | OBJ dosyaları, Wavefront’un Advanced Visualizer uygulaması tarafından geometrik nesneleri tanımlamak ve depolamak için kullanılır. Geometrik verilerin geri ve ileri iletimi OBJ dosyaları sayesinde mümkün olur. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/3d/obj). |
| static readonly [Ply](../../groupdocs.conversion.filetypes/threedfiletype/ply) | PLY, Polygon File Format, çokgen koleksiyonu olarak tanımlanan grafik nesnelerini depolayan bir 3D dosya formatını temsil eder. Bu dosya formatının amacı, geniş bir model yelpazesinde kullanılabilecek kadar genel, basit ve kolay bir dosya türü oluşturmaktı. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/3d/ply). |
| static readonly [Rvm](../../groupdocs.conversion.filetypes/threedfiletype/rvm) | RVM veri dosyaları AVEVA PDMS ile ilişkilidir. RVM dosyası, AVEVA Plant Design Management System Model proje dosyasıdır. AVEVA’nın Plant Design Management System (PDMS) projeleri yönetmek için veri odaklı teknoloji kullanan en popüler 3D tasarım sistemidir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/3d/rvm). |
| static readonly [ThreeDS](../../groupdocs.conversion.filetypes/threedfiletype/threeds) | .3ds uzantılı bir dosya, Autodesk 3D Studio tarafından kullanılan 3D Sudio (DOS) ağ dosya formatını temsil eder. Autodesk 3D Studio, 1990'lardan beri 3D dosya formatı pazarında bulunmakta ve şimdi 3D modelleme, animasyon ve render için 3D Studio MAX'e evrilmiştir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/3d/3ds). |
| static readonly [ThreeMF](../../groupdocs.conversion.filetypes/threedfiletype/threemf) | 3MF, 3D Manufacturing Format, uygulamalar tarafından 3D nesne modellerini çeşitli diğer uygulamalara, platformlara, hizmetlere ve yazıcılara aktarmak için kullanılır. En son 3D yazıcı sürümleriyle çalışmak için STL gibi diğer 3D dosya formatlarındaki sınırlamaları ve sorunları önlemek amacıyla geliştirilmiştir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/3d/3mf). |
| static readonly [U3d](../../groupdocs.conversion.filetypes/threedfiletype/u3d) | U3D (Universal 3D), 3D bilgisayar grafikleri için sıkıştırılmış bir dosya formatı ve veri yapısıdır. Üçgen ağlar, aydınlatma, gölgelendirme, hareket verileri, renkli çizgiler ve noktalar gibi 3D model bilgilerini içerir. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/3d/u3d). |
| static readonly [Usd](../../groupdocs.conversion.filetypes/threedfiletype/usd) | .usd uzantılı bir dosya, dijital içerik oluşturma uygulamaları arasında veri değişimi ve artırma amacıyla veri kodlayan Universal Scene Description dosya formatıdır. Pixar tarafından geliştirilen USD, öğe varlıklarını (örneğin modeller) veya animasyonları değiş tokuş etme yeteneği sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/3d/usd). |
| static readonly [Usdz](../../groupdocs.conversion.filetypes/threedfiletype/usdz) | .usdz uzantılı bir dosya, USD (Universal Scene Description) dosya formatı için sıkıştırılmamış ve şifrelenmemiş bir ZIP arşividir; arşiv içinde gömülü diğer formatların (örneğin dokular ve animasyonlar) dosyalarını içerir ve bunları doğrudan USD çalışma zamanı ile paket açmaya gerek kalmadan çalıştırır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/3d/usdz). |
| static readonly [Vrml](../../groupdocs.conversion.filetypes/threedfiletype/vrml) | Virtual Reality Modeling Language (VRML), World Wide Web (www) üzerinde etkileşimli 3D dünya nesnelerinin temsil edilmesi için bir dosya formatıdır. Karmaşık sahnelerin üç boyutlu temsillerini, örneğin illüstrasyonlar, tanımlar ve sanal gerçeklik sunumları oluşturmakta kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/3d/vrml). |
| static readonly [X](../../groupdocs.conversion.filetypes/threedfiletype/x) | .x uzantılı bir dosya, Microsoft DirectX 2.0 ile tanıtılan DirectX 3D Graphics eski dosya formatına işaret eder. Oyunlarda 3D grafik render'ı için kullanılmış ve ağlar, dokular, animasyonlar ve kullanıcı tanımlı nesneler için yapılandırmaları belirtir. 2014'ten beri Autodesk FBX dosya formatı daha modern bir seçenek olduğundan kullanımdan kaldırılmıştır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://docs.fileformat.com/3d/x). |

### Ayrıca Bakınız

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
