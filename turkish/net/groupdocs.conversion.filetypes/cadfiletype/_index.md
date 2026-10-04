---
title: "CadFileType"
second_title: "GroupDocs.Conversion for .NET API Referansı"
description: "CAD belgelerini (Computer Aided Design) tanımlar; bu belgeler 3D grafik dosya formatları için kullanılır ve 2D veya 3D tasarımlar içerebilir. Aşağıdaki türleri içerir Cf2./cadfiletype/cf2 Dgn./cadfiletype/dgn Dwf./cadfiletype/dwf Dwfx./cadfiletype/dwfx Dwg./cadfiletype/dwg Dwt./cadfiletype/dwt Dxf./cadfiletype/dxf Ifc./cadfiletype/ifc Igs./cadfiletype/igs Plt./cadfiletype/plt Stl./cadfiletype/stl. CAD formatları hakkında daha fazla bilgi edinin herehttps//wiki.fileformat.com/cad."
type: docs
weight: 1070
url: /tr/net/groupdocs.conversion.filetypes/cadfiletype/
---
## CadFileType class

CAD belgelerini (Computer Aided Design) tanımlar; bu belgeler 3D grafik dosya formatları için kullanılır ve 2D veya 3D tasarımlar içerebilir. Aşağıdaki türleri içerir: [`Cf2`](./cf2)[`Dgn`](./dgn), [`Dwf`](./dwf), [`Dwfx`](./dwfx)[`Dwg`](./dwg), [`Dwt`](./dwt), [`Dxf`](./dxf), [`Ifc`](./ifc), [`Igs`](./igs), [`Plt`](./plt), [`Stl`](./stl). CAD formatları hakkında daha fazla bilgi edinin [here](https://wiki.fileformat.com/cad).

```csharp
public sealed class CadFileType : FileType
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [CadFileType](cadfiletype)() | Serileştirme yapıcısı |

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
| static readonly [Cf2](../../groupdocs.conversion.filetypes/cadfiletype/cf2) | Common File Format Dosyası. 3D paket tasarımları veya diğer model verilerini içeren CAD dosyası; bir die kesme cihazı gibi bir CAD/CAM makinesi tarafından işlenebilir ve kesilebilir. |
| static readonly [Dgn](../../groupdocs.conversion.filetypes/cadfiletype/dgn) | DGN, Design dosyaları, MicroStation ve Intergraph Interactive Graphics Design System gibi CAD uygulamaları tarafından oluşturulan ve desteklenen çizimlerdir. Bu dosya formatı hakkında daha fazla bilgi edinin [here](https://wiki.fileformat.com/cad/dgn). |
| static readonly [Dwf](../../groupdocs.conversion.filetypes/cadfiletype/dwf) | Design Web Format (DWF), tasarım dosyalarını görüntüleme, inceleme veya yazdırma amacıyla sıkıştırılmış formatta 2D/3D çizim olarak temsil eder. Tasarım verilerinin bir parçası olarak grafik ve metin içerir ve sıkıştırılmış formatı sayesinde dosya boyutunu azaltır. Bu dosya formatı hakkında daha fazla bilgi edinin [here](https://wiki.fileformat.com/cad/dwf). |
| static readonly [Dwfx](../../groupdocs.conversion.filetypes/cadfiletype/dwfx) | DWFX dosyası, Autodesk CAD yazılımı ile oluşturulan 2D veya 3D bir çizimdir. DWFx formatında kaydedilir; bu format, . DWF dosyasına benzer, ancak Microsoft'un XML Paper Specification (XPS) kullanılarak biçimlendirilir. |
| static readonly [Dwg](../../groupdocs.conversion.filetypes/cadfiletype/dwg) | DWG uzantılı dosyalar, 2D ve 3D tasarım verilerini içeren özel ikili dosyaları temsil eder. ASCII dosyalar olan DXF gibi, DWG CAD (Computer Aided Design) çizimleri için ikili dosya formatını temsil eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/cad/dwg). |
| static readonly [Dwt](../../groupdocs.conversion.filetypes/cadfiletype/dwt) | DWT dosyası, DWG dosyaları olarak kaydedilebilecek çizimler oluşturmak için başlangıç olarak kullanılan bir AutoCAD çizim şablonu dosyasıdır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/cad/dwt). |
| static readonly [Dxf](../../groupdocs.conversion.filetypes/cadfiletype/dxf) | DXF, Drawing Interchange Format veya Drawing Exchange Format, AutoCAD çizim dosyasının etiketli veri temsilidır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/cad/dxf). |
| static readonly [Ifc](../../groupdocs.conversion.filetypes/cadfiletype/ifc) | IFC uzantılı dosyalar, bina nesnelerini ve özelliklerini içe ve dışa aktarmak için uluslararası standartlar belirleyen Industry Foundation Classes (IFC) dosya formatını ifade eder. Bu dosya formatı, farklı yazılım uygulamaları arasında birlikte çalışabilirlik sağlar. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/cad/ifc). |
| static readonly [Igs](../../groupdocs.conversion.filetypes/cadfiletype/igs) | Igs belge formatı |
| static readonly [Plt](../../groupdocs.conversion.filetypes/cadfiletype/plt) | PLT dosya formatı, Autodesk, Inc. tarafından tanıtılan ve belirli bir CAD dosyası için bilgi içeren vektör tabanlı bir plotter dosyasıdır. Çizim detayları üretimde doğruluk ve hassasiyet gerektirir ve PLT dosyasının kullanımı, tüm görüntülerin nokta yerine çizgiyle basılması sayesinde bunu garanti eder. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/cad/plt). |
| static readonly [Stl](../../groupdocs.conversion.filetypes/cadfiletype/stl) | STL, stereolithrography'nin kısaltmasıdır, 3 boyutlu yüzey geometrisini temsil eden değiştirilebilir bir dosya formatıdır. Bu dosya formatı, hızlı prototipleme, 3D baskı ve bilgisayar destekli imalat gibi çeşitli alanlarda kullanılır. Bu dosya formatı hakkında daha fazla bilgi edinin [burada](https://wiki.fileformat.com/cad/stl). |

### Ayrıca Bakınız

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
